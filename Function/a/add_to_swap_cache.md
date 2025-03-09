# Function: <code>add_to_swap_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580755952,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:119",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:add_to_swap"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580755952,
      "name": "add_to_swap_cache",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580878242,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:119",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:add_to_swap"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878016,
      "name": "add_to_swap_cache",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580946290,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:121",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:add_to_swap"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580946048,
      "name": "add_to_swap_cache",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580990560,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:140",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990560,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581094480,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:160",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581094480,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp_mask)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581235184,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:160",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581235184,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581317760,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:113",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581317760,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 763
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
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581428784,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:114",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581428784,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581493024,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:114",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581493024,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581699248,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:113",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581699248,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 749
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
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp, void * * shadowp)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581746192,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:128",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581746192,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 817
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
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp, void * * shadowp)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581773968,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:100",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581773968,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 837
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
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp, void * * shadowp)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:100",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592208885,
      "name": "add_to_swap_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071582056560,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1008
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
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp, void * * shadowp)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:101",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593986913,
      "name": "add_to_swap_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071582493328,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1530
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
int add_to_swap_cache(struct folio * folio, swp_entry_t entry, gfp_t gfp, void * * shadowp)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:88",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596038839,
      "name": "add_to_swap_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071583008336,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1026
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
int add_to_swap_cache(struct folio * folio, swp_entry_t entry, gfp_t gfp, void * * shadowp)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:87",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596561047,
      "name": "add_to_swap_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071583216656,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1033
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
int add_to_swap_cache(struct folio * folio, swp_entry_t entry, gfp_t gfp, void * * shadowp)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:87",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597466638,
      "name": "add_to_swap_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071583452160,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 917
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
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492912296,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:114",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492912296,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
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
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226703868,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:114",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226703868,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 940
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
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286317904,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:114",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286317904,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1148
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
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272835490,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:114",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272835490,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 798
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
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581461872,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:114",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581461872,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581404064,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:114",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581404064,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581453072,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:114",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581453072,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
int add_to_swap_cache(struct page * page, swp_entry_t entry, gfp_t gfp)
```

```json
{
  "name": "add_to_swap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581517536,
      "name": "add_to_swap_cache",
      "external": true,
      "loc": "mm/swap_state.c:114",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517536,
      "name": "add_to_swap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * * shadowp</code>
</li>
</ul>
</details>
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
