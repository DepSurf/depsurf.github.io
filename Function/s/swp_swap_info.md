# Function: <code>swp_swap_info</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581098741,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3465",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swapin_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581122304,
      "name": "swp_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581239557,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3489",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581262800,
      "name": "swp_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581322981,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3467",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345680,
      "name": "swp_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581433973,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3471",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping",
        "mm/swapfile.c:map_swap_entry",
        "mm/swapfile.c:get_swap_device",
        "mm/swapfile.c:_swap_info_get"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:total_swapcache_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455984,
      "name": "swp_swap_info",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581498213,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3479",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping",
        "mm/swapfile.c:map_swap_entry",
        "mm/swapfile.c:get_swap_device",
        "mm/swapfile.c:_swap_info_get"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:total_swapcache_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581520144,
      "name": "swp_swap_info",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581703973,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3533",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping",
        "mm/swapfile.c:map_swap_entry",
        "mm/swapfile.c:__swap_count",
        "mm/swapfile.c:_swap_info_get"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:total_swapcache_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581727664,
      "name": "swp_swap_info",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581751701,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3553",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping",
        "mm/swapfile.c:map_swap_page",
        "mm/swapfile.c:__swap_count",
        "mm/swapfile.c:_swap_info_get",
        "mm/swapfile.c:swap_page_sector"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:total_swapcache_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581775712,
      "name": "swp_swap_info",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581779525,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3524",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping",
        "mm/swapfile.c:__swap_count",
        "mm/swapfile.c:_swap_info_get",
        "mm/swapfile.c:swap_page_sector"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581803264,
      "name": "swp_swap_info",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582062965,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3525",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping",
        "mm/swapfile.c:get_swap_device",
        "mm/swapfile.c:_swap_info_get",
        "mm/swapfile.c:swap_page_sector"
      ],
      "caller_func": [
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582088096,
      "name": "swp_swap_info",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582501621,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3380",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapcache_mapping",
        "mm/swapfile.c:get_swap_device",
        "mm/swapfile.c:_swap_info_get",
        "mm/swapfile.c:swap_page_sector"
      ],
      "caller_func": [
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528032,
      "name": "swp_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583015701,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3382",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapcache_mapping",
        "mm/swapfile.c:get_swap_device",
        "mm/swapfile.c:_swap_info_get",
        "mm/swapfile.c:swap_page_sector"
      ],
      "caller_func": [
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583042560,
      "name": "swp_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583224389,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3370",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapcache_mapping",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swap_count",
        "mm/swapfile.c:get_swap_device",
        "mm/swapfile.c:_swap_info_get",
        "mm/swapfile.c:swap_page_sector"
      ],
      "caller_func": [
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583251168,
      "name": "swp_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583459813,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3381",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapcache_mapping",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swap_count",
        "mm/swapfile.c:get_swap_device",
        "mm/swapfile.c:_swap_info_get",
        "mm/swapfile.c:swap_folio_sector"
      ],
      "caller_func": [
        "mm/page_io.c:swap_read_folio",
        "mm/page_io.c:swap_read_folio_fs",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage_fs",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583485840,
      "name": "swp_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492919056,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3479",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping",
        "mm/swapfile.c:map_swap_page",
        "mm/swapfile.c:get_swap_device",
        "mm/swapfile.c:_swap_info_get"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:total_swapcache_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492943424,
      "name": "swp_swap_info",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226709620,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3479",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping",
        "mm/swapfile.c:map_swap_entry",
        "mm/swapfile.c:get_swap_device",
        "mm/swapfile.c:_swap_info_get"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:total_swapcache_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226729724,
      "name": "swp_swap_info",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286326080,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3479",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping",
        "mm/swapfile.c:map_swap_page",
        "mm/swapfile.c:get_swap_device",
        "mm/swapfile.c:_swap_info_get"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:total_swapcache_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286356848,
      "name": "swp_swap_info",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272840422,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3479",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping",
        "mm/swapfile.c:map_swap_page",
        "mm/swapfile.c:get_swap_device",
        "mm/swapfile.c:_swap_info_get"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:total_swapcache_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272860724,
      "name": "swp_swap_info",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581466949,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3479",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping",
        "mm/swapfile.c:map_swap_entry",
        "mm/swapfile.c:get_swap_device",
        "mm/swapfile.c:_swap_info_get"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:total_swapcache_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581488880,
      "name": "swp_swap_info",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581409205,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3479",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping",
        "mm/swapfile.c:map_swap_entry",
        "mm/swapfile.c:get_swap_device",
        "mm/swapfile.c:_swap_info_get"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:total_swapcache_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581431136,
      "name": "swp_swap_info",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581458261,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3479",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping",
        "mm/swapfile.c:map_swap_entry",
        "mm/swapfile.c:get_swap_device",
        "mm/swapfile.c:_swap_info_get"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:total_swapcache_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581480192,
      "name": "swp_swap_info",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```

```json
{
  "name": "swp_swap_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581522693,
      "name": "swp_swap_info",
      "external": true,
      "loc": "mm/swapfile.c:3479",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__page_file_mapping",
        "mm/swapfile.c:map_swap_entry",
        "mm/swapfile.c:get_swap_device",
        "mm/swapfile.c:_swap_info_get"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:total_swapcache_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581544928,
      "name": "swp_swap_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct swap_info_struct * swp_swap_info(swp_entry_t entry)
```
</details>
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
