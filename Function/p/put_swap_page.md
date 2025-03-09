# Function: <code>put_swap_page</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void put_swap_page(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "put_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580999824,
      "name": "put_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1194",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580999824,
      "name": "put_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
void put_swap_page(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "put_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581111296,
      "name": "put_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1264",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581111296,
      "name": "put_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 649
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
void put_swap_page(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "put_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581247200,
      "name": "put_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1264",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247200,
      "name": "put_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
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
void put_swap_page(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "put_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581330624,
      "name": "put_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1225",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581330624,
      "name": "put_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 751
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
void put_swap_page(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "put_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581440336,
      "name": "put_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1325",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581440336,
      "name": "put_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 758
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
void put_swap_page(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "put_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581504560,
      "name": "put_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1325",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581504560,
      "name": "put_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 758
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
void put_swap_page(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "put_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581712448,
      "name": "put_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1362",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581712448,
      "name": "put_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
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
void put_swap_page(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "put_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581760368,
      "name": "put_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1380",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581760368,
      "name": "put_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
void put_swap_page(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "put_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581787328,
      "name": "put_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1379",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581787328,
      "name": "put_swap_page",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void put_swap_page(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "put_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582071376,
      "name": "put_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1348",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582071376,
      "name": "put_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 841
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
void put_swap_page(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "put_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582511296,
      "name": "put_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1331",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:folio_alloc_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582511296,
      "name": "put_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 933
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void put_swap_page(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "put_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492925496,
      "name": "put_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1325",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492925496,
      "name": "put_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
void put_swap_page(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "put_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226714032,
      "name": "put_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1325",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226714032,
      "name": "put_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void put_swap_page(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "put_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286333616,
      "name": "put_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1325",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286333616,
      "name": "put_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
void put_swap_page(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "put_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272845232,
      "name": "put_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1325",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272845232,
      "name": "put_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
void put_swap_page(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "put_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581473296,
      "name": "put_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1325",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581473296,
      "name": "put_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 758
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
void put_swap_page(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "put_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581414704,
      "name": "put_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1325",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414704,
      "name": "put_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 758
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
void put_swap_page(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "put_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581464608,
      "name": "put_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1325",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581464608,
      "name": "put_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 758
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
void put_swap_page(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "put_swap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581529344,
      "name": "put_swap_page",
      "external": true,
      "loc": "mm/swapfile.c:1325",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581529344,
      "name": "put_swap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 751
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void put_swap_page(struct page * page, swp_entry_t entry)
```
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void put_swap_page(struct page * page, swp_entry_t entry)
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
