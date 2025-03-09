# Function: <code>xas_nomem</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "xas_nomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589428288,
      "name": "xas_nomem",
      "external": true,
      "loc": "lib/xarray.c:290",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:grab_mapping_entry",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_store_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589428288,
      "name": "xas_nomem",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "xas_nomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589886192,
      "name": "xas_nomem",
      "external": true,
      "loc": "lib/xarray.c:295",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:grab_mapping_entry",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_store_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589886192,
      "name": "xas_nomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "xas_nomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590112144,
      "name": "xas_nomem",
      "external": true,
      "loc": "lib/xarray.c:296",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:grab_mapping_entry",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_store_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590112144,
      "name": "xas_nomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "xas_nomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585113632,
      "name": "xas_nomem",
      "external": true,
      "loc": "lib/xarray.c:296",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:grab_mapping_entry",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_store_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585113632,
      "name": "xas_nomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "xas_nomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585263120,
      "name": "xas_nomem",
      "external": true,
      "loc": "lib/xarray.c:297",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:grab_mapping_entry",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_store_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585263120,
      "name": "xas_nomem",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "xas_nomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585145952,
      "name": "xas_nomem",
      "external": true,
      "loc": "lib/xarray.c:297",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:grab_mapping_entry",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_store_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585145952,
      "name": "xas_nomem",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "xas_nomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585595408,
      "name": "xas_nomem",
      "external": true,
      "loc": "lib/xarray.c:297",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:grab_mapping_entry",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_store_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585595408,
      "name": "xas_nomem",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "xas_nomem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586756416,
      "name": "xas_nomem",
      "external": true,
      "loc": "lib/xarray.c:300",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:grab_mapping_entry",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_store_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586756416,
      "name": "xas_nomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "xas_nomem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595923104,
      "name": "xas_nomem",
      "external": true,
      "loc": "lib/xarray.c:300",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:grab_mapping_entry",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_store_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595923104,
      "name": "xas_nomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "xas_nomem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596441856,
      "name": "xas_nomem",
      "external": true,
      "loc": "lib/xarray.c:298",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:grab_mapping_entry",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_store_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596441856,
      "name": "xas_nomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "xas_nomem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597337216,
      "name": "xas_nomem",
      "external": true,
      "loc": "lib/xarray.c:298",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:grab_mapping_entry",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_store_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597337216,
      "name": "xas_nomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "xas_nomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503893776,
      "name": "xas_nomem",
      "external": true,
      "loc": "lib/xarray.c:296",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:xa_store_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503893776,
      "name": "xas_nomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "xas_nomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236522580,
      "name": "xas_nomem",
      "external": true,
      "loc": "lib/xarray.c:296",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236522580,
      "name": "xas_nomem",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "xas_nomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297761376,
      "name": "xas_nomem",
      "external": true,
      "loc": "lib/xarray.c:296",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:grab_mapping_entry",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_store_range",
        "lib/xarray.c:xa_store_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297761376,
      "name": "xas_nomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "xas_nomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279784032,
      "name": "xas_nomem",
      "external": true,
      "loc": "lib/xarray.c:296",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279784032,
      "name": "xas_nomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "xas_nomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589714400,
      "name": "xas_nomem",
      "external": true,
      "loc": "lib/xarray.c:296",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:grab_mapping_entry",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_store_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589714400,
      "name": "xas_nomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "xas_nomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589440176,
      "name": "xas_nomem",
      "external": true,
      "loc": "lib/xarray.c:296",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:grab_mapping_entry",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_store_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589440176,
      "name": "xas_nomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "xas_nomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590157776,
      "name": "xas_nomem",
      "external": true,
      "loc": "lib/xarray.c:296",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:grab_mapping_entry",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_store_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590157776,
      "name": "xas_nomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
```

```json
{
  "name": "xas_nomem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590208320,
      "name": "xas_nomem",
      "external": true,
      "loc": "lib/xarray.c:296",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:grab_mapping_entry",
        "lib/idr.c:ida_alloc_range",
        "lib/xarray.c:xa_store_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590208320,
      "name": "xas_nomem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
bool xas_nomem(struct xa_state * xas, gfp_t gfp)
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
