# Function: <code>swapin_readahead</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580757088,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:465",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/memory.c:handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757088,
      "name": "swapin_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580879440,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:471",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580879440,
      "name": "swapin_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580947536,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:471",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580947536,
      "name": "swapin_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580992224,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:490",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580992224,
      "name": "swapin_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581096400,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:554",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096400,
      "name": "swapin_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 663
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
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581238128,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:791",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581238128,
      "name": "swapin_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1212
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
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581321536,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:753",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321536,
      "name": "swapin_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1225
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
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581432608,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:781",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581432608,
      "name": "swapin_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1135
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
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581496848,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:781",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581496848,
      "name": "swapin_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1135
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
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581703776,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:799",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581703776,
      "name": "swapin_readahead",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751504,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:893",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751504,
      "name": "swapin_readahead",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581779328,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:862",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581779328,
      "name": "swapin_readahead",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:849",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592209166,
      "name": "swapin_readahead.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071582062704,
      "name": "swapin_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:863",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593987231,
      "name": "swapin_readahead.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582501296,
      "name": "swapin_readahead",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:847",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596039222,
      "name": "swapin_readahead.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071583015328,
      "name": "swapin_readahead",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:856",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596561352,
      "name": "swapin_readahead.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071583224016,
      "name": "swapin_readahead",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:878",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597466974,
      "name": "swapin_readahead.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583459296,
      "name": "swapin_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492917168,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:781",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492917168,
      "name": "swapin_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 996
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
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226708016,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:781",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226708016,
      "name": "swapin_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1112
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
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286324144,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:781",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286324144,
      "name": "swapin_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1528
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
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272839132,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:781",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272839132,
      "name": "swapin_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 820
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
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581465568,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:739",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581465568,
      "name": "swapin_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1140
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
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581407872,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:781",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581407872,
      "name": "swapin_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1100
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
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581456896,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:781",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581456896,
      "name": "swapin_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1135
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
struct page * swapin_readahead(swp_entry_t entry, gfp_t gfp_mask, struct vm_fault * vmf)
```

```json
{
  "name": "swapin_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581521328,
      "name": "swapin_readahead",
      "external": true,
      "loc": "mm/swap_state.c:781",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581521328,
      "name": "swapin_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1135
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_fault * vmf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr</code>
</li>
</ul>
</details>
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
