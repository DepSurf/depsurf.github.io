# Function: <code>folio_add_lru</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void folio_add_lru(struct folio * folio)
```

```json
{
  "name": "folio_add_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582019408,
      "name": "folio_add_lru",
      "external": true,
      "loc": "mm/swap.c:456",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_add_folio",
        "mm/folio-compat.c:lru_cache_add",
        "mm/folio-compat.c:lru_cache_add",
        "mm/vmscan.c:reclaim_page_list",
        "mm/shmem.c:shmem_getpage_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019408,
      "name": "folio_add_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void folio_add_lru(struct folio * folio)
```

```json
{
  "name": "folio_add_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582448400,
      "name": "folio_add_lru",
      "external": true,
      "loc": "mm/swap.c:531",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_add_folio",
        "mm/swap.c:folio_add_lru_vma",
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:reclaim_folio_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_folios_to_lru",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_replace_folio",
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/khugepaged.c:collapse_file",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582448400,
      "name": "folio_add_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void folio_add_lru(struct folio * folio)
```

```json
{
  "name": "folio_add_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582653520,
      "name": "folio_add_lru",
      "external": true,
      "loc": "mm/swap.c:501",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_add_folio",
        "mm/swap.c:folio_add_lru_vma",
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:reclaim_folio_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_folios_to_lru",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_replace_folio",
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/migrate.c:migrate_pages_batch",
        "mm/khugepaged.c:collapse_file",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582653520,
      "name": "folio_add_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
void folio_add_lru(struct folio * folio)
```

```json
{
  "name": "folio_add_lru",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582824672,
      "name": "folio_add_lru",
      "external": true,
      "loc": "mm/swap.c:501",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_add_folio",
        "mm/swap.c:folio_add_lru_vma",
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:reclaim_folio_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_folios_to_lru",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_alloc_and_add_folio",
        "mm/memory.c:do_swap_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/migrate.c:migrate_pages_batch",
        "mm/khugepaged.c:collapse_file",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582824672,
      "name": "folio_add_lru",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void folio_add_lru(struct folio * folio)
```
</details>
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
