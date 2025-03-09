# Function: <code>__xas_next</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void * __xas_next(struct xa_state * xas)
```

```json
{
  "name": "__xas_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589425856,
      "name": "__xas_next",
      "external": true,
      "loc": "lib/xarray.c:1009",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:page_cache_next_miss",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589425856,
      "name": "__xas_next",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void * __xas_next(struct xa_state * xas)
```

```json
{
  "name": "__xas_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589883728,
      "name": "__xas_next",
      "external": true,
      "loc": "lib/xarray.c:1028",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:page_cache_next_miss",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589883728,
      "name": "__xas_next",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void * __xas_next(struct xa_state * xas)
```

```json
{
  "name": "__xas_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590109648,
      "name": "__xas_next",
      "external": true,
      "loc": "lib/xarray.c:1033",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:page_cache_next_miss",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590109648,
      "name": "__xas_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void * __xas_next(struct xa_state * xas)
```

```json
{
  "name": "__xas_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585114640,
      "name": "__xas_next",
      "external": true,
      "loc": "lib/xarray.c:1033",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:page_cache_next_miss",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585114640,
      "name": "__xas_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void * __xas_next(struct xa_state * xas)
```

```json
{
  "name": "__xas_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585264144,
      "name": "__xas_next",
      "external": true,
      "loc": "lib/xarray.c:1183",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:page_cache_next_miss",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585264144,
      "name": "__xas_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void * __xas_next(struct xa_state * xas)
```

```json
{
  "name": "__xas_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585146976,
      "name": "__xas_next",
      "external": true,
      "loc": "lib/xarray.c:1184",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_read_batch",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:page_cache_next_miss",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/iov_iter.c:iter_xarray_populate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585146976,
      "name": "__xas_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void * __xas_next(struct xa_state * xas)
```

```json
{
  "name": "__xas_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xas_next",
      "external": true,
      "loc": "lib/xarray.c:1184",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_read_batch",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:page_cache_next_miss",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/iov_iter.c:iter_xarray_populate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592345357,
      "name": "__xas_next.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071585598560,
      "name": "__xas_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
void * __xas_next(struct xa_state * xas)
```

```json
{
  "name": "__xas_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xas_next",
      "external": true,
      "loc": "lib/xarray.c:1191",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_read_batch",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:page_cache_next_miss",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/iov_iter.c:iter_xarray_populate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594206857,
      "name": "__xas_next.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071586756576,
      "name": "__xas_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void * __xas_next(struct xa_state * xas)
```

```json
{
  "name": "__xas_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xas_next",
      "external": true,
      "loc": "lib/xarray.c:1191",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_read_batch",
        "mm/filemap.c:filemap_get_folios_contig",
        "mm/filemap.c:page_cache_next_miss",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/iov_iter.c:iter_xarray_populate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596375537,
      "name": "__xas_next.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071595920224,
      "name": "__xas_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void * __xas_next(struct xa_state * xas)
```

```json
{
  "name": "__xas_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xas_next",
      "external": true,
      "loc": "lib/xarray.c:1189",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_read_batch",
        "mm/filemap.c:filemap_get_folios_contig",
        "mm/filemap.c:page_cache_next_miss",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/iov_iter.c:iter_xarray_populate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596905053,
      "name": "__xas_next.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071596438512,
      "name": "__xas_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void * __xas_next(struct xa_state * xas)
```

```json
{
  "name": "__xas_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__xas_next",
      "external": true,
      "loc": "lib/xarray.c:1189",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_get_read_batch",
        "mm/filemap.c:filemap_get_folios_contig",
        "mm/filemap.c:page_cache_next_miss",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/iov_iter.c:iter_xarray_populate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597830146,
      "name": "__xas_next.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071597333872,
      "name": "__xas_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void * __xas_next(struct xa_state * xas)
```

```json
{
  "name": "__xas_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503891040,
      "name": "__xas_next",
      "external": true,
      "loc": "lib/xarray.c:1033",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:page_cache_next_miss",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503891040,
      "name": "__xas_next",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * __xas_next(struct xa_state * xas)
```

```json
{
  "name": "__xas_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236519660,
      "name": "__xas_next",
      "external": true,
      "loc": "lib/xarray.c:1033",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:page_cache_next_miss",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236519660,
      "name": "__xas_next",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * __xas_next(struct xa_state * xas)
```

```json
{
  "name": "__xas_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297757648,
      "name": "__xas_next",
      "external": true,
      "loc": "lib/xarray.c:1033",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:page_cache_next_miss",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297757648,
      "name": "__xas_next",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * __xas_next(struct xa_state * xas)
```

```json
{
  "name": "__xas_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279782472,
      "name": "__xas_next",
      "external": true,
      "loc": "lib/xarray.c:1033",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:page_cache_next_miss",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279782472,
      "name": "__xas_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void * __xas_next(struct xa_state * xas)
```

```json
{
  "name": "__xas_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589711904,
      "name": "__xas_next",
      "external": true,
      "loc": "lib/xarray.c:1033",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:page_cache_next_miss",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589711904,
      "name": "__xas_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void * __xas_next(struct xa_state * xas)
```

```json
{
  "name": "__xas_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589437680,
      "name": "__xas_next",
      "external": true,
      "loc": "lib/xarray.c:1033",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:page_cache_next_miss",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589437680,
      "name": "__xas_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void * __xas_next(struct xa_state * xas)
```

```json
{
  "name": "__xas_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590155280,
      "name": "__xas_next",
      "external": true,
      "loc": "lib/xarray.c:1033",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:page_cache_next_miss",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590155280,
      "name": "__xas_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void * __xas_next(struct xa_state * xas)
```

```json
{
  "name": "__xas_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590205664,
      "name": "__xas_next",
      "external": true,
      "loc": "lib/xarray.c:1033",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:page_cache_next_miss",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590205664,
      "name": "__xas_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void * __xas_next(struct xa_state * xas)
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
