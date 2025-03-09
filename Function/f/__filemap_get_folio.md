# Function: <code>__filemap_get_folio</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct folio * __filemap_get_folio(struct address_space * mapping, long unsigned int index, int fgp_flags, gfp_t gfp)
```

```json
{
  "name": "__filemap_get_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__filemap_get_folio",
      "external": true,
      "loc": "mm/filemap.c:1940",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/folio-compat.c:pagecache_get_page",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/buffer.c:nobh_truncate_page",
        "fs/verity/enable.c:read_file_data_page",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593964992,
      "name": "__filemap_get_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071581940800,
      "name": "__filemap_get_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 946
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
struct folio * __filemap_get_folio(struct address_space * mapping, long unsigned int index, int fgp_flags, gfp_t gfp)
```

```json
{
  "name": "__filemap_get_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__filemap_get_folio",
      "external": true,
      "loc": "mm/filemap.c:1910",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/folio-compat.c:pagecache_get_page",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:filemap_get_incore_folio",
        "mm/swap_state.c:filemap_get_incore_folio",
        "mm/swap_state.c:swap_cache_get_folio",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596024365,
      "name": "__filemap_get_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071582375728,
      "name": "__filemap_get_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 951
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
struct folio * __filemap_get_folio(struct address_space * mapping, long unsigned int index, int fgp_flags, gfp_t gfp)
```

```json
{
  "name": "__filemap_get_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582584368,
      "name": "__filemap_get_folio",
      "external": true,
      "loc": "mm/filemap.c:1882",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/folio-compat.c:pagecache_get_page",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:filemap_get_incore_folio",
        "mm/swap_state.c:swap_cache_get_folio",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__getblk_slow",
        "fs/buffer.c:__find_get_block_slow",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582584368,
      "name": "__filemap_get_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
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
struct folio * __filemap_get_folio(struct address_space * mapping, long unsigned int index, fgf_t fgp_flags, gfp_t gfp)
```

```json
{
  "name": "__filemap_get_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582755600,
      "name": "__filemap_get_folio",
      "external": true,
      "loc": "mm/filemap.c:1848",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/folio-compat.c:pagecache_get_page",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:filemap_get_incore_folio",
        "mm/swap_state.c:swap_cache_get_folio",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "fs/libfs.c:simple_write_begin",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__getblk_slow",
        "fs/buffer.c:__find_get_block_slow",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_get_folio",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582755600,
      "name": "__filemap_get_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 739
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
struct folio * __filemap_get_folio(struct address_space * mapping, long unsigned int index, int fgp_flags, gfp_t gfp)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int fgp_flags</code> ➡️ <code>fgf_t fgp_flags</code>
</li>
</ul>
</details>
</li>
</ul>
