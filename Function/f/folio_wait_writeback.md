# Function: <code>folio_wait_writeback</code>

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
void folio_wait_writeback(struct folio * folio)
```

```json
{
  "name": "folio_wait_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581977392,
      "name": "folio_wait_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:3006",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:folio_wait_stable",
        "mm/page-writeback.c:folio_write_one",
        "mm/page-writeback.c:folio_write_one",
        "mm/folio-compat.c:wait_on_page_writeback",
        "mm/folio-compat.c:wait_on_page_writeback",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "fs/splice.c:page_cache_pipe_buf_try_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581977392,
      "name": "folio_wait_writeback",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void folio_wait_writeback(struct folio * folio)
```

```json
{
  "name": "folio_wait_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582412448,
      "name": "folio_wait_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:3144",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:folio_wait_stable",
        "mm/page-writeback.c:folio_write_one",
        "mm/page-writeback.c:folio_write_one",
        "mm/folio-compat.c:wait_on_page_writeback",
        "mm/folio-compat.c:wait_on_page_writeback",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/vmscan.c:shrink_folio_list",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "fs/splice.c:page_cache_pipe_buf_try_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582412448,
      "name": "folio_wait_writeback",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void folio_wait_writeback(struct folio * folio)
```

```json
{
  "name": "folio_wait_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582618912,
      "name": "folio_wait_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:3085",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:folio_wait_stable",
        "mm/page-writeback.c:write_cache_pages",
        "mm/folio-compat.c:wait_on_page_writeback",
        "mm/folio-compat.c:wait_on_page_writeback",
        "mm/folio-compat.c:wait_on_page_writeback",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/vmscan.c:shrink_folio_list",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/migrate.c:migrate_folio_unmap",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582618912,
      "name": "folio_wait_writeback",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void folio_wait_writeback(struct folio * folio)
```

```json
{
  "name": "folio_wait_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582790432,
      "name": "folio_wait_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:3057",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:folio_wait_stable",
        "mm/page-writeback.c:write_cache_pages",
        "mm/folio-compat.c:wait_on_page_writeback",
        "mm/folio-compat.c:wait_on_page_writeback",
        "mm/folio-compat.c:wait_on_page_writeback",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/vmscan.c:shrink_folio_list",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/migrate.c:migrate_folio_unmap",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582790432,
      "name": "folio_wait_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void folio_wait_writeback(struct folio * folio)
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
