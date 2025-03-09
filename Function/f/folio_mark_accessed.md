# Function: <code>folio_mark_accessed</code>

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
void folio_mark_accessed(struct folio * folio)
```

```json
{
  "name": "folio_mark_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582014080,
      "name": "folio_mark_accessed",
      "external": true,
      "loc": "mm/swap.c:418",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_read",
        "mm/filemap.c:filemap_read",
        "mm/filemap.c:__filemap_get_folio",
        "mm/folio-compat.c:mark_page_accessed",
        "mm/folio-compat.c:mark_page_accessed",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_folio",
        "fs/iomap/buffered-io.c:iomap_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582014080,
      "name": "folio_mark_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void folio_mark_accessed(struct folio * folio)
```

```json
{
  "name": "folio_mark_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582452080,
      "name": "folio_mark_accessed",
      "external": true,
      "loc": "mm/swap.c:488",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_read",
        "mm/filemap.c:filemap_read",
        "mm/filemap.c:__filemap_get_folio",
        "mm/folio-compat.c:mark_page_accessed",
        "mm/folio-compat.c:mark_page_accessed",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_swapin_folio",
        "fs/iomap/buffered-io.c:iomap_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582452080,
      "name": "folio_mark_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
void folio_mark_accessed(struct folio * folio)
```

```json
{
  "name": "folio_mark_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582657344,
      "name": "folio_mark_accessed",
      "external": true,
      "loc": "mm/swap.c:458",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_splice_read",
        "mm/filemap.c:filemap_read",
        "mm/filemap.c:filemap_read",
        "mm/filemap.c:__filemap_get_folio",
        "mm/folio-compat.c:mark_page_accessed",
        "mm/folio-compat.c:mark_page_accessed",
        "mm/folio-compat.c:mark_page_accessed",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_swapin_folio",
        "fs/iomap/buffered-io.c:iomap_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582657344,
      "name": "folio_mark_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void folio_mark_accessed(struct folio * folio)
```

```json
{
  "name": "folio_mark_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582828480,
      "name": "folio_mark_accessed",
      "external": true,
      "loc": "mm/swap.c:458",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_splice_read",
        "mm/filemap.c:filemap_read",
        "mm/filemap.c:filemap_read",
        "mm/filemap.c:__filemap_get_folio",
        "mm/folio-compat.c:mark_page_accessed",
        "mm/folio-compat.c:mark_page_accessed",
        "mm/folio-compat.c:mark_page_accessed",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/memory.c:zap_pte_range",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "drivers/gpu/drm/drm_gem.c:drm_gem_put_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582828480,
      "name": "folio_mark_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void folio_mark_accessed(struct folio * folio)
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
