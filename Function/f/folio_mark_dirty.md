# Function: <code>folio_mark_dirty</code>

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
bool folio_mark_dirty(struct folio * folio)
```

```json
{
  "name": "folio_mark_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581976144,
      "name": "folio_mark_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2705",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/folio-compat.c:set_page_dirty",
        "mm/folio-compat.c:set_page_dirty",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/swap_state.c:add_to_swap",
        "fs/buffer.c:nobh_truncate_page",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581976144,
      "name": "folio_mark_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
bool folio_mark_dirty(struct folio * folio)
```

```json
{
  "name": "folio_mark_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582411120,
      "name": "folio_mark_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2843",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/folio-compat.c:set_page_dirty",
        "mm/folio-compat.c:set_page_dirty",
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:walk_pte_range",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/swap_state.c:add_to_swap",
        "mm/hugetlb.c:hugetlb_add_to_page_cache",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/khugepaged.c:collapse_file",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582411120,
      "name": "folio_mark_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
bool folio_mark_dirty(struct folio * folio)
```

```json
{
  "name": "folio_mark_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582617568,
      "name": "folio_mark_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2784",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/folio-compat.c:set_page_dirty",
        "mm/folio-compat.c:set_page_dirty",
        "mm/folio-compat.c:set_page_dirty",
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:walk_pte_range",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/swap_state.c:add_to_swap",
        "mm/hugetlb.c:hugetlb_add_to_page_cache",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/khugepaged.c:collapse_file",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:write_end_fn",
        "fs/ext4/inode.c:do_journal_get_write_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582617568,
      "name": "folio_mark_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool folio_mark_dirty(struct folio * folio)
```

```json
{
  "name": "folio_mark_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582789088,
      "name": "folio_mark_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2763",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/folio-compat.c:set_page_dirty",
        "mm/folio-compat.c:set_page_dirty",
        "mm/folio-compat.c:set_page_dirty",
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:walk_pte_range",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:zap_pte_range",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:__end_swap_bio_write",
        "mm/swap_state.c:add_to_swap",
        "mm/zswap.c:zswap_load",
        "mm/hugetlb.c:hugetlb_add_to_page_cache",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/khugepaged.c:collapse_file",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:write_end_fn",
        "fs/ext4/inode.c:do_journal_get_write_access",
        "block/bio.c:bio_set_pages_dirty",
        "block/bio.c:__bio_release_pages",
        "drivers/gpu/drm/drm_gem.c:drm_gem_put_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582789088,
      "name": "folio_mark_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool folio_mark_dirty(struct folio * folio)
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
