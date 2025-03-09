# Function: <code>try_to_free_swap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580764656,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:953",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:handle_mm_fault",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swapfile.c:scan_swap_map",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764656,
      "name": "try_to_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580887232,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:952",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:scan_swap_map",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580887232,
      "name": "try_to_free_swap",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580955408,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:972",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:scan_swap_map",
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955408,
      "name": "try_to_free_swap",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581001568,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1381",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581001568,
      "name": "try_to_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581114016,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1590",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581114016,
      "name": "try_to_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581249840,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1590",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581249840,
      "name": "try_to_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581333408,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1584",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581333408,
      "name": "try_to_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581443184,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1693",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/ksm.c:replace_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581443184,
      "name": "try_to_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581507408,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1693",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/ksm.c:replace_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581507408,
      "name": "try_to_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581714400,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1730",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/ksm.c:replace_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714400,
      "name": "try_to_free_swap.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071581715552,
      "name": "try_to_free_swap",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581762288,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1748",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/ksm.c:replace_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581762288,
      "name": "try_to_free_swap.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071581763472,
      "name": "try_to_free_swap",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581790512,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1747",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/ksm.c:replace_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790512,
      "name": "try_to_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582074576,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1716",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/ksm.c:replace_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582074576,
      "name": "try_to_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582513728,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1591",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/ksm.c:replace_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582513728,
      "name": "try_to_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492928504,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1693",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492928504,
      "name": "try_to_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226716264,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1693",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/ksm.c:replace_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226716264,
      "name": "try_to_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286337456,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1693",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/ksm.c:replace_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286337456,
      "name": "try_to_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272848048,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1693",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272848048,
      "name": "try_to_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581476144,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1693",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/ksm.c:replace_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581476144,
      "name": "try_to_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581417552,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1693",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/ksm.c:replace_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581417552,
      "name": "try_to_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581467456,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1693",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/ksm.c:replace_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581467456,
      "name": "try_to_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int try_to_free_swap(struct page * page)
```

```json
{
  "name": "try_to_free_swap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581532256,
      "name": "try_to_free_swap",
      "external": true,
      "loc": "mm/swapfile.c:1693",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:do_swap_page",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/ksm.c:replace_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581532256,
      "name": "try_to_free_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int try_to_free_swap(struct page * page)
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
