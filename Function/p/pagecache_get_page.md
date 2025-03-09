# Function: <code>pagecache_get_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580475312,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1132",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/mincore.c:mincore_page",
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swapfile.c:scan_swap_map",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/splice.c:__generic_file_splice_read",
        "fs/splice.c:__generic_file_splice_read",
        "fs/buffer.c:__find_get_block_slow",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/aio.c:SyS_io_setup",
        "fs/dax.c:__dax_fault",
        "fs/dax.c:__dax_fault",
        "fs/dax.c:__dax_fault",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580475312,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580553360,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1183",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/mincore.c:mincore_page",
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:scan_swap_map",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/namei.c:page_get_link",
        "fs/splice.c:__generic_file_splice_read",
        "fs/splice.c:__generic_file_splice_read",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:__find_get_block_slow",
        "fs/aio.c:aio_setup_ring",
        "fs/dax.c:dax_fault",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580553360,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 663
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580617872,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1285",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/mincore.c:mincore_page",
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:scan_swap_map",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:__getblk_gfp",
        "fs/aio.c:aio_setup_ring",
        "fs/dax.c:dax_iomap_fault",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580617872,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 663
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580647872,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1413",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/mincore.c:mincore_page",
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:__getblk_gfp",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647872,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580731568,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1535",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/mincore.c:mincore_page",
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:__getblk_gfp",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580731568,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580866960,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1535",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/mincore.c:mincore_page",
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:__getblk_gfp",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866960,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 695
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580938048,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1573",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/mincore.c:mincore_page",
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:__getblk_gfp",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_emit",
        "fs/fuse/readdir.c:fuse_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580938048,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 695
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581032272,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1626",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/mincore.c:mincore_page",
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:__getblk_gfp",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_emit",
        "fs/fuse/readdir.c:fuse_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581032272,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581087824,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1629",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/mincore.c:mincore_page",
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:__getblk_gfp",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_emit",
        "fs/fuse/readdir.c:fuse_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581087824,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 763
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int index, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581277536,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1600",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/mincore.c:mincore_page",
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:__find_get_block_slow",
        "fs/aio.c:aio_setup_ring",
        "fs/verity/enable.c:read_file_data_page",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_get_buddy_page_lock",
        "fs/ext4/mballoc.c:ext4_mb_get_buddy_page_lock",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581277536,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 882
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int index, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581324160,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1792",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:find_get_incore_page",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:__find_get_block_slow",
        "fs/aio.c:aio_setup_ring",
        "fs/verity/enable.c:read_file_data_page",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_get_buddy_page_lock",
        "fs/ext4/mballoc.c:ext4_mb_get_buddy_page_lock",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581324160,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 936
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int index, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581335520,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1833",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:find_get_incore_page",
        "mm/swap_state.c:find_get_incore_page",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:__find_get_block_slow",
        "fs/aio.c:aio_setup_ring",
        "fs/verity/enable.c:read_file_data_page",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache",
        "lib/buildid.c:build_id_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581335520,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1303
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int index, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1888",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:find_get_incore_page",
        "mm/swap_state.c:find_get_incore_page",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/secretmem.c:secretmem_fault",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:__find_get_block_slow",
        "fs/aio.c:aio_setup_ring",
        "fs/verity/enable.c:read_file_data_page",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache",
        "lib/buildid.c:build_id_parse",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592189744,
      "name": "pagecache_get_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071581583712,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1413
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int index, int fgp_flags, gfp_t gfp)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581993472,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/folio-compat.c:121",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/folio-compat.c:grab_cache_page_write_begin",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/shmem.c:shmem_get_link",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:find_get_incore_page",
        "mm/swap_state.c:find_get_incore_page",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/secretmem.c:secretmem_fault",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:__find_get_block_slow",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache",
        "lib/buildid.c:build_id_parse",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581993472,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int index, int fgp_flags, gfp_t gfp)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582429920,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/folio-compat.c:93",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/folio-compat.c:grab_cache_page_write_begin",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/secretmem.c:secretmem_fault",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:grow_dev_page",
        "fs/buffer.c:__find_get_block_slow",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/verity.c:ext4_read_merkle_tree_page",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "lib/buildid.c:build_id_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582429920,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int index, int fgp_flags, gfp_t gfp)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582635104,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/folio-compat.c:94",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/folio-compat.c:grab_cache_page_write_begin",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/secretmem.c:secretmem_fault",
        "fs/namei.c:page_get_link",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/squashfs/block.c:squashfs_bio_read",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache",
        "lib/buildid.c:build_id_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582635104,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int index, fgf_t fgp_flags, gfp_t gfp)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582806480,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/folio-compat.c:88",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/folio-compat.c:grab_cache_page_write_begin",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/khugepaged.c:collapse_file",
        "mm/secretmem.c:secretmem_fault",
        "fs/namei.c:page_get_link",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/squashfs/block.c:squashfs_bio_read",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/fuse/dev.c:fuse_notify_store",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache",
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache",
        "lib/buildid.c:build_id_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582806480,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492454480,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1629",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/mincore.c:mincore_page",
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:__getblk_gfp",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_emit",
        "fs/fuse/readdir.c:fuse_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492454480,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226327896,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1629",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/mincore.c:mincore_page",
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:__getblk_slow",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_retrieve",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226327896,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 896
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285729408,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1629",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/mincore.c:mincore_page",
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:__getblk_gfp",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_emit",
        "fs/fuse/readdir.c:fuse_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285729408,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1244
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272525908,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1629",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/mincore.c:mincore_page",
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:__getblk_gfp",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_emit",
        "fs/fuse/readdir.c:fuse_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272525908,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581056672,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1629",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/mincore.c:mincore_page",
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:__getblk_gfp",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_emit",
        "fs/fuse/readdir.c:fuse_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581056672,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 763
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581003920,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1629",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/mincore.c:mincore_page",
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:__getblk_gfp",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_emit",
        "fs/fuse/readdir.c:fuse_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003920,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 763
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581047872,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1629",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/mincore.c:mincore_page",
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:__getblk_gfp",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_emit",
        "fs/fuse/readdir.c:fuse_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581047872,
      "name": "pagecache_get_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 763
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
struct page * pagecache_get_page(struct address_space * mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask)
```

```json
{
  "name": "pagecache_get_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581109568,
      "name": "pagecache_get_page",
      "external": true,
      "loc": "mm/filemap.c:1629",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:grab_cache_page_write_begin",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/mincore.c:mincore_page",
        "mm/mincore.c:mincore_page",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/namei.c:page_get_link",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:__getblk_gfp",
        "fs/aio.c:aio_setup_ring",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_emit",
        "fs/fuse/readdir.c:fuse_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581109568,
      "name": "pagecache_get_page",
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

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int index</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int offset</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
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
