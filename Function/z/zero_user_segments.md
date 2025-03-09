# Function: <code>zero_user_segments</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580545587,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580584826,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581158243,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581221993,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:guard_bio_eod",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581246624,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581260881,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562529,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597761,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581820974,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581861170,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_readpage_inline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581871840,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582008253,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582082458,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_short_read",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_write_end"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580634763,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580680470,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581323361,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581388451,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:guard_bio_eod",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581412974,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581426613,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583013,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581754529,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581788626,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582016716,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582058055,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582068150,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582222566,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309169,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_short_read"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580701869,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580746464,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581402535,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581466931,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:guard_bio_eod",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581493632,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581507829,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581668293,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581842765,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581878221,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582106764,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582147703,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582158182,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582312070,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582397500,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_short_read"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580735830,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580781907,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581457590,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581522483,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:guard_bio_eod",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581548562,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581559903,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581722745,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581967356,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992337,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582076983,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582114972,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115873,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582396903,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582481804,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:193",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_short_read"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580822598,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580868563,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581599635,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664749,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:guard_bio_eod",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581691765,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581703882,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581868797,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582116396,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582141876,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582227922,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582263996,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265772,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582547627,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582632793,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_short_read"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580959228,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581004854,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581756677,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581828059,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:guard_bio_eod",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581859885,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581871228,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582051417,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582304897,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582330898,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582417702,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582452236,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582453519,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582738989,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582826340,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:194",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_short_read"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581035452,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581080680,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581843157,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581915307,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:guard_bio_eod",
        "fs/buffer.c:guard_bio_eod",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581944665,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581956318,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582142895,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_read_page_sync",
        "fs/iomap.c:iomap_read_page_sync",
        "fs/iomap.c:iomap_readpage_actor",
        "fs/iomap.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582403521,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582429503,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582517161,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582551713,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582553009,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582842749,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582928932,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_short_read"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581099378,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581144336,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581967740,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582052457,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:guard_bio_eod",
        "fs/buffer.c:guard_bio_eod",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582080785,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582089001,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582301790,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582573601,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582598783,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582684634,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582724005,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582725508,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583017836,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583107741,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_short_read"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581156318,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201872,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582040828,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582137331,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582158225,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582166431,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582400814,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582674561,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582699519,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582786810,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582826535,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582828410,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583124028,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583213229,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583955498,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_truncate"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581342123,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:287",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581388310,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:287",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582275554,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:287",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582370403,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:287",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_expand_zero",
        "fs/buffer.c:cont_expand_zero",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:page_zero_new_buffers",
        "fs/buffer.c:page_zero_new_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582395964,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:287",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582402571,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:287",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582698111,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:287",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582986087,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:287",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583011629,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:287",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583099919,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:287",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583138128,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:287",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583140579,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:287",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583444162,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:287",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583541237,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:287",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584344383,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:287",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void zero_user_segments(struct page * page, unsigned int start1, unsigned int end1, unsigned int start2, unsigned int end2)
```

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581379968,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ]
    },
    {
      "addr": 18446744071581429296,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    },
    {
      "addr": 18446744071582326096,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ]
    },
    {
      "addr": 18446744071582414288,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_expand_zero",
        "fs/buffer.c:cont_expand_zero",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:page_zero_new_buffers"
      ]
    },
    {
      "addr": 18446744071582446496,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_direct_IO"
      ]
    },
    {
      "addr": 18446744071582454432,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    },
    {
      "addr": 18446744071582760032,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    },
    {
      "addr": 18446744071583061691,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_read_inline_page"
      ]
    },
    {
      "addr": 18446744071583073248,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ]
    },
    {
      "addr": 18446744071583178000,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    },
    {
      "addr": 18446744071583215296,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    },
    {
      "addr": 18446744071583221370,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    },
    {
      "addr": 18446744071583556932,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end"
      ]
    },
    {
      "addr": 18446744071583635344,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin"
      ]
    },
    {
      "addr": 18446744071584459448,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379968,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071581429296,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071582326096,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071582414288,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    },
    {
      "addr": 18446744071582446496,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071582454432,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071582760032,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    },
    {
      "addr": 18446744071583055616,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583073248,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071583178000,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071583215296,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583218960,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583555344,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583635344,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void zero_user_segments(struct page * page, unsigned int start1, unsigned int end1, unsigned int start2, unsigned int end2)
```

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581400880,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ]
    },
    {
      "addr": 18446744071581449872,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    },
    {
      "addr": 18446744071582354032,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ]
    },
    {
      "addr": 18446744071582441488,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_expand_zero",
        "fs/buffer.c:cont_expand_zero",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:page_zero_new_buffers"
      ]
    },
    {
      "addr": 18446744071582473296,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_direct_IO"
      ]
    },
    {
      "addr": 18446744071582481488,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    },
    {
      "addr": 18446744071582791920,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    },
    {
      "addr": 18446744071583087097,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline"
      ],
      "caller_func": [
        "fs/ext4/inline.c:ext4_read_inline_page"
      ]
    },
    {
      "addr": 18446744071583098608,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ]
    },
    {
      "addr": 18446744071583204624,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    },
    {
      "addr": 18446744071583242800,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    },
    {
      "addr": 18446744071583249225,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    },
    {
      "addr": 18446744071583580184,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end"
      ]
    },
    {
      "addr": 18446744071583655600,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin"
      ]
    },
    {
      "addr": 18446744071584493759,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:215",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400880,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071581449872,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071582354032,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071582441488,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071582473296,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071582481488,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071582791920,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071583082032,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583098608,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071583204624,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071583242800,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583246800,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583578592,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071583655600,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void zero_user_segments(struct page * page, unsigned int start1, unsigned int end1, unsigned int start2, unsigned int end2)
```

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:201",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ]
    },
    {
      "addr": 18446744071581704400,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:201",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    },
    {
      "addr": 18446744071582675313,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:201",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ]
    },
    {
      "addr": 18446744071582764610,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:201",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_expand_zero",
        "fs/buffer.c:cont_expand_zero",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:201",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:201",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    },
    {
      "addr": 18446744071583113826,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:201",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:201",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ]
    },
    {
      "addr": 18446744071583438481,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:201",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:201",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:201",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:201",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    },
    {
      "addr": 18446744071583937005,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:201",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:201",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin"
      ]
    },
    {
      "addr": 18446744071584902236,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:201",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581651744,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071592191416,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071581704192,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    },
    {
      "addr": 18446744071592192276,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071582675104,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
    },
    {
      "addr": 18446744071592231086,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071582764400,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446744071592231765,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071582785648,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071592233259,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071582794448,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071592235008,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583113616,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446744071592244860,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071583420992,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071592257170,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583438272,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
    },
    {
      "addr": 18446744071592257497,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071583547904,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071592266100,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583584832,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071592267176,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583589584,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071592267384,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583936864,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071592282985,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071584014160,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071592288366,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void zero_user_segments(struct page * page, unsigned int start1, unsigned int end1, unsigned int start2, unsigned int end2)
```

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_partial_folio"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_write_end"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/secretmem.c:secretmem_free_folio",
        "mm/secretmem.c:secretmem_free_folio"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_read_folio"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_expand_zero",
        "fs/buffer.c:cont_expand_zero",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_begin_int"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:guard_bio_eod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582022768,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071593967125,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071582086720,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 629
    },
    {
      "addr": 18446744071593968304,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071582922432,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
    },
    {
      "addr": 18446744071594007471,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583220976,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    },
    {
      "addr": 18446744071594011055,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071583314416,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
    },
    {
      "addr": 18446744071594011922,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071583338320,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071594013493,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071583346560,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
    },
    {
      "addr": 18446744071594015241,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583596800,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
    },
    {
      "addr": 18446744071594024139,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071583939984,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
    },
    {
      "addr": 18446744071594038217,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583958816,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
    },
    {
      "addr": 18446744071594038847,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071584082080,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071594047587,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071584122272,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
    },
    {
      "addr": 18446744071594048633,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071584127344,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
    },
    {
      "addr": 18446744071594048853,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071584434240,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071594059086,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071584517424,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
    },
    {
      "addr": 18446744071594065384,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071584601680,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    },
    {
      "addr": 18446744071594070418,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071585602496,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071594095442,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void zero_user_segments(struct page * page, unsigned int start1, unsigned int end1, unsigned int start2, unsigned int end2)
```

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_partial_folio"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_writepage"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/secretmem.c:secretmem_free_folio",
        "mm/secretmem.c:secretmem_free_folio"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_read_folio"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:cont_expand_zero",
        "fs/buffer.c:cont_expand_zero",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_begin_int"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:272",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:guard_bio_eod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582454656,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071596025655,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071582557984,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
    },
    {
      "addr": 18446744071596027128,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071583477904,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071596049738,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583800096,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446744071596051717,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071583900976,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446744071596052165,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071583920704,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071596053278,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071583930288,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
    },
    {
      "addr": 18446744071596055122,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071584202112,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
    },
    {
      "addr": 18446744071596059650,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071584566544,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
    },
    {
      "addr": 18446744071596071222,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071584586112,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446744071596071852,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071584714976,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071596080469,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071584755856,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
    },
    {
      "addr": 18446744071596081465,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071584761312,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
    },
    {
      "addr": 18446744071596081631,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071585096464,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071596087415,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071585187488,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
    },
    {
      "addr": 18446744071596090521,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071585280336,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071596091040,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071586370688,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071596104652,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void zero_user_segments(struct page * page, unsigned int start1, unsigned int end1, unsigned int start2, unsigned int end2)
```

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_partial_folio"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_writepage"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/secretmem.c:secretmem_free_folio"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_read_folio"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:cont_expand_zero",
        "fs/buffer.c:cont_expand_zero",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:folio_zero_new_buffers"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_direct_IO"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_folio"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_bio_write_folio"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:guard_bio_eod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582659920,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071596547798,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071582763696,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    },
    {
      "addr": 18446744071596549428,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071583694672,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071596572181,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071584017088,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    },
    {
      "addr": 18446744071596574247,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071584124128,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071596574688,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071584143376,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071596576082,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071584154352,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071596577707,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071584432272,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071596583835,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071584795616,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071596594667,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071584811280,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071596594970,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071584938944,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071596603635,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071584979568,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071596604590,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071584984864,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071596604904,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585326224,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071596610777,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585416592,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
    },
    {
      "addr": 18446744071596613812,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071585510864,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071596614432,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071586617152,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071596628503,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void zero_user_segments(struct page * page, unsigned int start1, unsigned int end1, unsigned int start2, unsigned int end2)
```

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_partial_folio"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_writepage"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/secretmem.c:secretmem_free_folio"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/libfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_read_folio"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_write_full_folio",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:cont_expand_zero",
        "fs/buffer.c:cont_expand_zero",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:folio_zero_new_buffers"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_direct_IO"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_readpage_inline"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_bio_write_folio"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin"
      ]
    },
    {
      "addr": 0,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:268",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:guard_bio_eod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582830848,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071597451514,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071582939392,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    },
    {
      "addr": 18446744071597453100,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071583889056,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071597476699,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071584230048,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071597478785,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071584341920,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071597479511,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071584359728,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071597480428,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584368544,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071597481758,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071584653424,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071597488406,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071585028880,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071597500206,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071585044544,
      "name": "zero_user_segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    },
    {
      "addr": 18446744071597500466,
      "name": "zero_user_segments.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071585170512,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071597509082,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071585212320,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071597510267,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071585216336,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071597510583,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071585560912,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071597516667,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071585651392,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    },
    {
      "addr": 18446744071597519766,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071585747632,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071597520337,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071586888032,
      "name": "zero_user_segments.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071597534475,
      "name": "zero_user_segments.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492534272,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492584424,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493566728,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493682564,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493712040,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493720592,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494003280,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494327396,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494356656,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494456620,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494497952,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494500868,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494834156,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494933692,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495777176,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_truncate"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226399464,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226447276,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3227115544,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 3227208452,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 3227238904,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 3227246364,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 3227467420,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 3227762868,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3227789660,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 3227891440,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 3227934856,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3227936928,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 3228253376,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 3228343864,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 3229129220,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_truncate"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285830048,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285903572,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287141040,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287285328,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287317388,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287326312,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287653540,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288051064,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288086168,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288209996,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288263328,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288266148,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288680620,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288805424,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289951804,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_truncate"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272585386,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272621212,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273223850,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273305910,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273325372,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273332016,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273517900,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273764136,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273785980,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273864094,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273896820,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273898760,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274157568,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274240122,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274921734,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_truncate"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581125166,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581170720,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582009564,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582106067,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582126961,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135167,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582369550,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582643297,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582668255,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582755546,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582795271,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582797146,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583092764,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583181965,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583924234,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_truncate"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581072142,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581117536,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581947132,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582043507,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582064401,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072607,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582307246,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582580465,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582605423,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582692714,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582732423,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582734298,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583029916,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583119117,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583861178,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_truncate"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581116366,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581161920,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582000844,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582096547,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582117441,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582125647,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582360030,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582633153,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582658111,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582745402,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582784151,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582786026,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583081372,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583165997,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583907994,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_truncate"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zero_user_segments",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581178790,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581228181,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072044,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582169443,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582190408,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582198639,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582439694,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582716369,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582741778,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582830650,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582870519,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582872436,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583170700,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583259533,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584009258,
      "name": "zero_user_segments",
      "external": false,
      "loc": "include/linux/highmem.h:218",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_truncate"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void zero_user_segments(struct page * page, unsigned int start1, unsigned int end1, unsigned int start2, unsigned int end2)
```
</details>
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
