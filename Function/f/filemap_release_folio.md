# Function: <code>filemap_release_folio</code>

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
bool filemap_release_folio(struct folio * folio, gfp_t gfp)
```

```json
{
  "name": "filemap_release_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581922400,
      "name": "filemap_release_folio",
      "external": true,
      "loc": "mm/filemap.c:3965",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/folio-compat.c:try_to_release_page",
        "mm/folio-compat.c:try_to_release_page",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:mapping_evict_folio",
        "mm/vmscan.c:shrink_page_list",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:block_invalidate_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581922400,
      "name": "filemap_release_folio",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool filemap_release_folio(struct folio * folio, gfp_t gfp)
```

```json
{
  "name": "filemap_release_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582359456,
      "name": "filemap_release_folio",
      "external": true,
      "loc": "mm/filemap.c:3959",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:mapping_evict_folio",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/migrate.c:move_to_new_folio",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:truncate_error_page",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:block_invalidate_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582359456,
      "name": "filemap_release_folio",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool filemap_release_folio(struct folio * folio, gfp_t gfp)
```

```json
{
  "name": "filemap_release_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582562784,
      "name": "filemap_release_folio",
      "external": true,
      "loc": "mm/filemap.c:4072",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:mapping_evict_folio",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/migrate.c:move_to_new_folio",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:truncate_error_page",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:block_invalidate_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582562784,
      "name": "filemap_release_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
bool filemap_release_folio(struct folio * folio, gfp_t gfp)
```

```json
{
  "name": "filemap_release_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582733504,
      "name": "filemap_release_folio",
      "external": true,
      "loc": "mm/filemap.c:4079",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:mapping_evict_folio",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/migrate.c:move_to_new_folio",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:truncate_error_folio",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:block_invalidate_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582733504,
      "name": "filemap_release_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
bool filemap_release_folio(struct folio * folio, gfp_t gfp)
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
