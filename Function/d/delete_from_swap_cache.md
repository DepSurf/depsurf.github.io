# Function: <code>delete_from_swap_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580756240,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:212",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/swapfile.c:reuse_swap_page",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756240,
      "name": "delete_from_swap_cache",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580878320,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:216",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878320,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580946368,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:218",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580946368,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580991008,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:236",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580991008,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581094944,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:267",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581094944,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581235648,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:264",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:reuse_swap_page",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581235648,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581319040,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:243",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:reuse_swap_page",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319040,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581430096,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:244",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581430096,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581494320,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:244",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581494320,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581700528,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:243",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swapfile.c:reuse_swap_page",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581700528,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581747568,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:272",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swapfile.c:reuse_swap_page",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581747568,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581775392,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:243",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581775392,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582058224,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:240",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582058224,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582495712,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:245",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/swapfile.c:try_to_free_swap",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582495712,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void delete_from_swap_cache(struct folio * folio)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583010176,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:231",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/swapfile.c:folio_free_swap",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583010176,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void delete_from_swap_cache(struct folio * folio)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583218512,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:234",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/swapfile.c:folio_free_swap",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583218512,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void delete_from_swap_cache(struct folio * folio)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583453872,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:234",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/swapfile.c:folio_free_swap",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583453872,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492913904,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:244",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492913904,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226705264,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:244",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:reuse_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226705264,
      "name": "delete_from_swap_cache",
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286319920,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:244",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286319920,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272836692,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:244",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:reuse_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272836692,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463168,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:244",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463168,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581405344,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:244",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581405344,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581454368,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:244",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581454368,
      "name": "delete_from_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void delete_from_swap_cache(struct page * page)
```

```json
{
  "name": "delete_from_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581518816,
      "name": "delete_from_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:244",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/swapfile.c:reuse_swap_page",
        "mm/memory-failure.c:me_swapcache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518816,
      "name": "delete_from_swap_cache",
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
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
</ul>
</details>
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
