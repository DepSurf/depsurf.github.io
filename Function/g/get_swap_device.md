# Function: <code>get_swap_device</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * get_swap_device(swp_entry_t entry)
```

```json
{
  "name": "get_swap_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_swap_device",
      "external": true,
      "loc": "mm/swapfile.c:1249",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swap_state.c:total_swapcache_pages",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:__swap_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581457146,
      "name": "get_swap_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581438912,
      "name": "get_swap_device",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * get_swap_device(swp_entry_t entry)
```

```json
{
  "name": "get_swap_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_swap_device",
      "external": true,
      "loc": "mm/swapfile.c:1249",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swap_state.c:total_swapcache_pages",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:__swap_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581521279,
      "name": "get_swap_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581503136,
      "name": "get_swap_device",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct swap_info_struct * get_swap_device(swp_entry_t entry)
```

```json
{
  "name": "get_swap_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581714597,
      "name": "get_swap_device",
      "external": true,
      "loc": "mm/swapfile.c:1285",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__swap_count"
      ],
      "caller_func": [
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swap_state.c:total_swapcache_pages",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swp_swapcount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581728843,
      "name": "get_swap_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581711872,
      "name": "get_swap_device",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct swap_info_struct * get_swap_device(swp_entry_t entry)
```

```json
{
  "name": "get_swap_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581762485,
      "name": "get_swap_device",
      "external": true,
      "loc": "mm/swapfile.c:1303",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__swap_count"
      ],
      "caller_func": [
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:find_get_incore_page",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swap_state.c:total_swapcache_pages",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swp_swapcount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591331692,
      "name": "get_swap_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581759760,
      "name": "get_swap_device",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct swap_info_struct * get_swap_device(swp_entry_t entry)
```

```json
{
  "name": "get_swap_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581789541,
      "name": "get_swap_device",
      "external": true,
      "loc": "mm/swapfile.c:1302",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__swap_count"
      ],
      "caller_func": [
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:find_get_incore_page",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swp_swapcount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591274339,
      "name": "get_swap_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581786752,
      "name": "get_swap_device",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * get_swap_device(swp_entry_t entry)
```

```json
{
  "name": "get_swap_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_swap_device",
      "external": true,
      "loc": "mm/swapfile.c:1265",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:find_get_incore_page",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:__swap_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592209350,
      "name": "get_swap_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071582070592,
      "name": "get_swap_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
struct swap_info_struct * get_swap_device(swp_entry_t entry)
```

```json
{
  "name": "get_swap_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_swap_device",
      "external": true,
      "loc": "mm/swapfile.c:1247",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:find_get_incore_page",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:__swap_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593987401,
      "name": "get_swap_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071582510480,
      "name": "get_swap_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
struct swap_info_struct * get_swap_device(swp_entry_t entry)
```

```json
{
  "name": "get_swap_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583029376,
      "name": "get_swap_device",
      "external": true,
      "loc": "mm/swapfile.c:1251",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:filemap_get_incore_folio",
        "mm/swap_state.c:swap_cache_get_folio",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:__swap_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583029376,
      "name": "get_swap_device",
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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct * get_swap_device(swp_entry_t entry)
```

```json
{
  "name": "get_swap_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583238976,
      "name": "get_swap_device",
      "external": true,
      "loc": "mm/swapfile.c:1257",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_folio",
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:filemap_get_incore_folio",
        "mm/swapfile.c:add_swap_count_continuation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583238976,
      "name": "get_swap_device",
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct swap_info_struct * get_swap_device(swp_entry_t entry)
```

```json
{
  "name": "get_swap_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583473504,
      "name": "get_swap_device",
      "external": true,
      "loc": "mm/swapfile.c:1257",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_folio",
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:filemap_get_incore_folio",
        "mm/swapfile.c:add_swap_count_continuation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583473504,
      "name": "get_swap_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct swap_info_struct * get_swap_device(swp_entry_t entry)
```

```json
{
  "name": "get_swap_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492924744,
      "name": "get_swap_device",
      "external": true,
      "loc": "mm/swapfile.c:1249",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swap_state.c:total_swapcache_pages",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:__swap_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492924744,
      "name": "get_swap_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct swap_info_struct * get_swap_device(swp_entry_t entry)
```

```json
{
  "name": "get_swap_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226713436,
      "name": "get_swap_device",
      "external": true,
      "loc": "mm/swapfile.c:1249",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swap_state.c:total_swapcache_pages",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:__swap_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226713436,
      "name": "get_swap_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct swap_info_struct * get_swap_device(swp_entry_t entry)
```

```json
{
  "name": "get_swap_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286332640,
      "name": "get_swap_device",
      "external": true,
      "loc": "mm/swapfile.c:1249",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swap_state.c:total_swapcache_pages",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:__swap_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286332640,
      "name": "get_swap_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct swap_info_struct * get_swap_device(swp_entry_t entry)
```

```json
{
  "name": "get_swap_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272844556,
      "name": "get_swap_device",
      "external": true,
      "loc": "mm/swapfile.c:1249",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swap_state.c:total_swapcache_pages",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:__swap_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272844556,
      "name": "get_swap_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * get_swap_device(swp_entry_t entry)
```

```json
{
  "name": "get_swap_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_swap_device",
      "external": true,
      "loc": "mm/swapfile.c:1249",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swap_state.c:total_swapcache_pages",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:__swap_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581490015,
      "name": "get_swap_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581471872,
      "name": "get_swap_device",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * get_swap_device(swp_entry_t entry)
```

```json
{
  "name": "get_swap_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_swap_device",
      "external": true,
      "loc": "mm/swapfile.c:1249",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swap_state.c:total_swapcache_pages",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:__swap_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581432271,
      "name": "get_swap_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581414128,
      "name": "get_swap_device",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * get_swap_device(swp_entry_t entry)
```

```json
{
  "name": "get_swap_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_swap_device",
      "external": true,
      "loc": "mm/swapfile.c:1249",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swap_state.c:total_swapcache_pages",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:__swap_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581481327,
      "name": "get_swap_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581463184,
      "name": "get_swap_device",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct swap_info_struct * get_swap_device(swp_entry_t entry)
```

```json
{
  "name": "get_swap_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_swap_device",
      "external": true,
      "loc": "mm/swapfile.c:1249",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swap_state.c:total_swapcache_pages",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:__swap_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581546079,
      "name": "get_swap_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071581527856,
      "name": "get_swap_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct swap_info_struct * get_swap_device(swp_entry_t entry)
```
</details>
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
