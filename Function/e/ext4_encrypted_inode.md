# Function: <code>ext4_encrypted_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_encrypted_inode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581534613,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:1536",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581538791,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:1536",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581549219,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:1536",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563389,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:1536",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597466,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:1536",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581599661,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:1536",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607754,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:1536",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581738797,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:1536",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_zeroout",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581872805,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:1536",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581879143,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:1536",
      "file": "fs/ext4/crypto_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/crypto_policy.c:ext4_is_child_context_consistent_with_parent",
        "fs/ext4/crypto_policy.c:ext4_is_child_context_consistent_with_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581886525,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:1536",
      "file": "fs/ext4/crypto_fname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/crypto_fname.c:ext4_fname_setup_filename"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool ext4_encrypted_inode(struct inode * inode)
```

```json
{
  "name": "ext4_encrypted_inode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581721991,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2295",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581724502,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2295",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/file.c:ext4_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581734971,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2295",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762942,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2295",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581788181,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2295",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581792770,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2295",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581807624,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2295",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581826944,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2295",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581966522,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2295",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582068701,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2295",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581826944,
      "name": "ext4_encrypted_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool ext4_encrypted_inode(struct inode * inode)
```

```json
{
  "name": "ext4_encrypted_inode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581809635,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2275",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581812086,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2275",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581816830,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2275",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581822563,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2275",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581874057,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2275",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581877749,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2275",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581897048,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2275",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581980481,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2275",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582055906,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2275",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582061921,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2275",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582100590,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2275",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582109910,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2275",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115940,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2275",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582149593,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2275",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582158721,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2275",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581916000,
      "name": "ext4_encrypted_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool ext4_encrypted_inode(struct inode * inode)
```

```json
{
  "name": "ext4_encrypted_inode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581881777,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2311",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581885560,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2311",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581917948,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2311",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581929211,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2311",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581939031,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2311",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946254,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2311",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581955185,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2311",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581969178,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2311",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582022919,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2311",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582065040,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2311",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582079843,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2311",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091496,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2311",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_cross_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_link",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582114521,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2311",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582117120,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2311",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582196839,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2311",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_on"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133104,
      "name": "ext4_encrypted_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_encrypted_inode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582031833,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2271",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582035594,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2271",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582068159,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2271",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582082158,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2271",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582087921,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2271",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582095592,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2271",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582104241,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2271",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582118397,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2271",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582173527,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2271",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582214527,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2271",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582229443,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2271",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582259131,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2271",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582263545,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2271",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582266219,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2271",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582345588,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2271",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_on"
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
  "name": "ext4_encrypted_inode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582220018,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2272",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582223686,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2272",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582256262,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2272",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582270212,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2272",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582276009,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2272",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582283347,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2272",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582292382,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2272",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582306580,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2272",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582363490,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2272",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582404379,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2272",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582419307,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2272",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582424285,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2272",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582451598,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2272",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582454083,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2272",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582534634,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2272",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_on"
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
  "name": "ext4_encrypted_inode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582314883,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2285",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582318582,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2285",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582352022,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2285",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582368859,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2285",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374682,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2285",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582382083,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2285",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:__ext4_new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582391134,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2285",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582405175,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2285",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582462498,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2285",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582503638,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2285",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582518780,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2285",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582523805,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2285",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582551066,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2285",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582553573,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2285",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582635738,
      "name": "ext4_encrypted_inode",
      "external": false,
      "loc": "fs/ext4/ext4.h:2285",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_on"
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
bool ext4_encrypted_inode(struct inode * inode)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
bool ext4_encrypted_inode(struct inode * inode)
```
</details>
</li>
</ul>
