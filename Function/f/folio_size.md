# Function: <code>folio_size</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "folio_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581952610,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1698",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582025108,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1698",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/truncate.c:truncate_cleanup_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582096590,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1698",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582380241,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1698",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582673776,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1698",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__ksize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582922852,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1698",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/secretmem.c:secretmem_free_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582936255,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1698",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:check_heap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583221989,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1698",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583309779,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1698",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583329360,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1698",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_is_partially_uptodate",
        "fs/buffer.c:block_is_partially_uptodate",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:block_invalidate_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583606091,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1698",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_invalidate_folio",
        "fs/iomap/buffered-io.c:iomap_release_folio",
        "fs/iomap/buffered-io.c:iomap_is_partially_uptodate",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio",
        "fs/iomap/buffered-io.c:iomap_read_inline_data",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "fs/iomap/buffered-io.c:iomap_page_release",
        "fs/iomap/buffered-io.c:iomap_page_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583960260,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1698",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/inode.c:__ext4_journalled_invalidate_folio",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584349573,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1698",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586081764,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1698",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
size_t folio_size(struct folio * folio)
```

```json
{
  "name": "folio_size",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582385038,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582459082,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/truncate.c:truncate_cleanup_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582578760,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582655623,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:__ksize",
        "mm/slab_common.c:__ksize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582883726,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583117765,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583140415,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:new_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583247090,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:unmap_and_move_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583425109,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583451592,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583478340,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/secretmem.c:secretmem_free_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583492246,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:check_heap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583800549,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583894207,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583902795,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_is_partially_uptodate",
        "fs/buffer.c:block_is_partially_uptodate",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:block_invalidate_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584210725,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_invalidate_folio",
        "fs/iomap/buffered-io.c:iomap_release_folio",
        "fs/iomap/buffered-io.c:iomap_is_partially_uptodate",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio",
        "fs/iomap/buffered-io.c:iomap_read_inline_data",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "fs/iomap/buffered-io.c:iomap_page_release",
        "fs/iomap/buffered-io.c:iomap_page_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584588468,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/inode.c:__ext4_journalled_invalidate_folio",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584999685,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586533964,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "block/partitions/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/core.c:read_part_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587063139,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:1831",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587042240,
      "name": "folio_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071596113992,
      "name": "folio_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
size_t folio_size(struct folio * folio)
```

```json
{
  "name": "folio_size",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582591249,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:splice_folio_into_pipe",
        "mm/filemap.c:splice_folio_into_pipe",
        "mm/filemap.c:filemap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582664263,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/truncate.c:truncate_cleanup_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582770717,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582865774,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:__ksize",
        "mm/slab_common.c:__ksize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583098566,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583328037,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:folio_putback_active_hugetlb",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583350594,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:new_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583462500,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:migrate_hugetlbs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583645509,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583671496,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583694914,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/secretmem.c:secretmem_free_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583707182,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:check_heap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584017477,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584117183,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584135179,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_is_partially_uptodate",
        "fs/buffer.c:block_is_partially_uptodate",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:folio_alloc_buffers",
        "fs/buffer.c:folio_alloc_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584148962,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_write_end_io",
        "fs/mpage.c:mpage_write_end_io",
        "fs/mpage.c:mpage_write_end_io",
        "fs/mpage.c:mpage_read_end_io",
        "fs/mpage.c:mpage_read_end_io",
        "fs/mpage.c:mpage_read_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584327170,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "fs/crypto/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/bio.c:fscrypt_decrypt_bio",
        "fs/crypto/bio.c:fscrypt_decrypt_bio",
        "fs/crypto/bio.c:fscrypt_decrypt_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584343655,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584440499,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_release_folio",
        "fs/iomap/buffered-io.c:iomap_is_partially_uptodate",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio",
        "fs/iomap/buffered-io.c:iomap_read_inline_data",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "fs/iomap/buffered-io.c:iomap_page_release",
        "fs/iomap/buffered-io.c:iomap_page_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584798595,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584859956,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/inode.c:__ext4_journalled_invalidate_folio",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_submit_folio",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584983503,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584987476,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:__read_end_io",
        "fs/ext4/readpage.c:__read_end_io",
        "fs/ext4/readpage.c:__read_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585211049,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:memcpy_from_file_folio",
        "fs/ext4/verity.c:memcpy_from_file_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585227621,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586780458,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "block/partitions/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/core.c:read_part_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587290353,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587314855,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2084",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:copy_page_to_iter_nofault",
        "lib/iov_iter.c:copy_page_to_iter_nofault",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587300112,
      "name": "folio_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071596639237,
      "name": "folio_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
size_t folio_size(struct folio * folio)
```

```json
{
  "name": "folio_size",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582762449,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:splice_folio_into_pipe",
        "mm/filemap.c:splice_folio_into_pipe",
        "mm/filemap.c:filemap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582835111,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/truncate.c:truncate_cleanup_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582946024,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583036964,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:__ksize",
        "mm/slab_common.c:__ksize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583192230,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583280800,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:folio_referenced_one",
        "mm/rmap.c:folio_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583451548,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_read_folio",
        "mm/page_io.c:swap_read_folio_bdev_sync",
        "mm/page_io.c:swap_read_folio_fs",
        "mm/page_io.c:swap_read_folio_fs",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage_bdev_sync",
        "mm/page_io.c:swap_writepage_fs",
        "mm/page_io.c:swap_writepage_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583564229,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:move_hugetlb_state",
        "mm/hugetlb.c:folio_putback_active_hugetlb",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:dissolve_free_huge_page",
        "mm/hugetlb.c:free_huge_folio",
        "mm/hugetlb.c:free_hpage_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583587370,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_migration_target_by_mpol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583655400,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:migrate_hugetlbs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583840293,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583866054,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583889306,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/secretmem.c:secretmem_free_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583907522,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:check_heap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584230530,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584335140,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584359149,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_write_full_folio",
        "fs/buffer.c:block_write_full_folio",
        "fs/buffer.c:block_write_full_folio",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_is_partially_uptodate",
        "fs/buffer.c:block_is_partially_uptodate",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:folio_alloc_buffers",
        "fs/buffer.c:folio_alloc_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584364184,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_write_end_io",
        "fs/mpage.c:mpage_read_end_io",
        "fs/mpage.c:bio_first_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584545254,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "fs/crypto/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/bio.c:fscrypt_decrypt_bio",
        "fs/crypto/bio.c:bio_first_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584562214,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584662906,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_iter",
        "fs/iomap/buffered-io.c:iomap_write_iter",
        "fs/iomap/buffered-io.c:iomap_write_iter",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_dirty_folio",
        "fs/iomap/buffered-io.c:iomap_release_folio",
        "fs/iomap/buffered-io.c:iomap_is_partially_uptodate",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio",
        "fs/iomap/buffered-io.c:iomap_read_inline_data",
        "fs/iomap/buffered-io.c:iomap_read_inline_data",
        "fs/iomap/buffered-io.c:iomap_read_inline_data",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:ifs_free",
        "fs/iomap/buffered-io.c:ifs_alloc",
        "fs/iomap/buffered-io.c:ifs_set_range_dirty",
        "fs/iomap/buffered-io.c:ifs_set_range_uptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585031475,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585092881,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/inode.c:__ext4_journalled_invalidate_folio",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_submit_folio",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585214860,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585219105,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:__read_end_io",
        "fs/ext4/readpage.c:__read_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585444513,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:memcpy_from_file_folio",
        "fs/ext4/verity.c:memcpy_from_file_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585460613,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585515987,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888367,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_set_pages_dirty",
        "block/bio.c:__bio_release_pages",
        "block/bio.c:bio_first_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587057199,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "block/partitions/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/core.c:read_part_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587576285,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587602693,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_to_iter_nofault",
        "lib/iov_iter.c:copy_page_to_iter_nofault"
      ],
      "caller_func": [
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_flushcache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter_nocache",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:_copy_to_iter",
        "lib/iov_iter.c:_copy_to_iter"
      ]
    },
    {
      "addr": 0,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:csum_and_copy_from_iter_full",
        "net/core/skbuff.c:csum_and_copy_from_iter_full"
      ]
    },
    {
      "addr": 0,
      "name": "folio_size",
      "external": false,
      "loc": "include/linux/mm.h:2139",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:csum_and_copy_to_iter",
        "net/core/datagram.c:csum_and_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587585536,
      "name": "folio_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071597547988,
      "name": "folio_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071594364272,
      "name": "folio_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071597776274,
      "name": "folio_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071594428976,
      "name": "folio_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071597777041,
      "name": "folio_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
size_t folio_size(struct folio * folio)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
