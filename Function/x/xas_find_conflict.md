# Function: <code>xas_find_conflict</code>

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
void * xas_find_conflict(struct xa_state * xas)
```

```json
{
  "name": "xas_find_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589427840,
      "name": "xas_find_conflict",
      "external": true,
      "loc": "lib/xarray.c:1206",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_add_to_page_cache",
        "fs/dax.c:get_unlocked_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589427840,
      "name": "xas_find_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
void * xas_find_conflict(struct xa_state * xas)
```

```json
{
  "name": "xas_find_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589885744,
      "name": "xas_find_conflict",
      "external": true,
      "loc": "lib/xarray.c:1225",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_add_to_page_cache",
        "fs/dax.c:get_unlocked_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589885744,
      "name": "xas_find_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
void * xas_find_conflict(struct xa_state * xas)
```

```json
{
  "name": "xas_find_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590111696,
      "name": "xas_find_conflict",
      "external": true,
      "loc": "lib/xarray.c:1236",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_add_to_page_cache",
        "fs/dax.c:get_unlocked_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590111696,
      "name": "xas_find_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
void * xas_find_conflict(struct xa_state * xas)
```

```json
{
  "name": "xas_find_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585110944,
      "name": "xas_find_conflict",
      "external": true,
      "loc": "lib/xarray.c:1238",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_add_to_page_cache",
        "fs/dax.c:get_unlocked_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585110944,
      "name": "xas_find_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
void * xas_find_conflict(struct xa_state * xas)
```

```json
{
  "name": "xas_find_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585260192,
      "name": "xas_find_conflict",
      "external": true,
      "loc": "lib/xarray.c:1388",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "fs/dax.c:get_unlocked_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585260192,
      "name": "xas_find_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
void * xas_find_conflict(struct xa_state * xas)
```

```json
{
  "name": "xas_find_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585143776,
      "name": "xas_find_conflict",
      "external": true,
      "loc": "lib/xarray.c:1389",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "fs/dax.c:get_unlocked_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585143776,
      "name": "xas_find_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
void * xas_find_conflict(struct xa_state * xas)
```

```json
{
  "name": "xas_find_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585595680,
      "name": "xas_find_conflict",
      "external": true,
      "loc": "lib/xarray.c:1389",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "fs/dax.c:get_unlocked_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585595680,
      "name": "xas_find_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
void * xas_find_conflict(struct xa_state * xas)
```

```json
{
  "name": "xas_find_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586754768,
      "name": "xas_find_conflict",
      "external": true,
      "loc": "lib/xarray.c:1396",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "fs/dax.c:get_unlocked_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586754768,
      "name": "xas_find_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
void * xas_find_conflict(struct xa_state * xas)
```

```json
{
  "name": "xas_find_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595919744,
      "name": "xas_find_conflict",
      "external": true,
      "loc": "lib/xarray.c:1396",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "fs/dax.c:get_unlocked_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595919744,
      "name": "xas_find_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
void * xas_find_conflict(struct xa_state * xas)
```

```json
{
  "name": "xas_find_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596438048,
      "name": "xas_find_conflict",
      "external": true,
      "loc": "lib/xarray.c:1394",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "fs/dax.c:get_unlocked_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596438048,
      "name": "xas_find_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
void * xas_find_conflict(struct xa_state * xas)
```

```json
{
  "name": "xas_find_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597333408,
      "name": "xas_find_conflict",
      "external": true,
      "loc": "lib/xarray.c:1394",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "fs/dax.c:get_unlocked_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597333408,
      "name": "xas_find_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
void * xas_find_conflict(struct xa_state * xas)
```

```json
{
  "name": "xas_find_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503893296,
      "name": "xas_find_conflict",
      "external": true,
      "loc": "lib/xarray.c:1236",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_add_to_page_cache",
        "fs/dax.c:get_unlocked_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503893296,
      "name": "xas_find_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
void * xas_find_conflict(struct xa_state * xas)
```

```json
{
  "name": "xas_find_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236522100,
      "name": "xas_find_conflict",
      "external": true,
      "loc": "lib/xarray.c:1236",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236522100,
      "name": "xas_find_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
void * xas_find_conflict(struct xa_state * xas)
```

```json
{
  "name": "xas_find_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297760688,
      "name": "xas_find_conflict",
      "external": true,
      "loc": "lib/xarray.c:1236",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_add_to_page_cache",
        "fs/dax.c:get_unlocked_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297760688,
      "name": "xas_find_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
void * xas_find_conflict(struct xa_state * xas)
```

```json
{
  "name": "xas_find_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279783702,
      "name": "xas_find_conflict",
      "external": true,
      "loc": "lib/xarray.c:1236",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_add_to_page_cache",
        "fs/dax.c:get_unlocked_entry",
        "fs/dax.c:get_unlocked_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279783702,
      "name": "xas_find_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
void * xas_find_conflict(struct xa_state * xas)
```

```json
{
  "name": "xas_find_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589713952,
      "name": "xas_find_conflict",
      "external": true,
      "loc": "lib/xarray.c:1236",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_add_to_page_cache",
        "fs/dax.c:get_unlocked_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589713952,
      "name": "xas_find_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
void * xas_find_conflict(struct xa_state * xas)
```

```json
{
  "name": "xas_find_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589439728,
      "name": "xas_find_conflict",
      "external": true,
      "loc": "lib/xarray.c:1236",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_add_to_page_cache",
        "fs/dax.c:get_unlocked_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589439728,
      "name": "xas_find_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
void * xas_find_conflict(struct xa_state * xas)
```

```json
{
  "name": "xas_find_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590157328,
      "name": "xas_find_conflict",
      "external": true,
      "loc": "lib/xarray.c:1236",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_add_to_page_cache",
        "fs/dax.c:get_unlocked_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590157328,
      "name": "xas_find_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
void * xas_find_conflict(struct xa_state * xas)
```

```json
{
  "name": "xas_find_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590207872,
      "name": "xas_find_conflict",
      "external": true,
      "loc": "lib/xarray.c:1236",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_add_to_page_cache",
        "fs/dax.c:get_unlocked_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590207872,
      "name": "xas_find_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
void * xas_find_conflict(struct xa_state * xas)
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
