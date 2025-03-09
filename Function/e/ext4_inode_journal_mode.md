# Function: <code>ext4_inode_journal_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581540935,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:392",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581543530,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:392",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582131856,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:392",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_page_mkwrite"
      ]
    },
    {
      "addr": 18446744071581698782,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:392",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581757092,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:392",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581776906,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:392",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581812490,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:392",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581823903,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:392",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581829702,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:392",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_ind_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581863376,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:392",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582131856,
      "name": "ext4_inode_journal_mode.part.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581726524,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581729165,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581784346,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
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
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    },
    {
      "addr": 18446744071581890929,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581965359,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581971759,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582008985,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582019823,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582025707,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582059346,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582349845,
      "name": "ext4_inode_journal_mode.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581815893,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581816765,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581873898,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    },
    {
      "addr": 18446744071581980321,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_on"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582055423,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582061775,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582099033,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582109855,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115803,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582149067,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:411",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441234,
      "name": "ext4_inode_journal_mode.part.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581885436,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581917637,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581932980,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581938817,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581954876,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581968963,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582022849,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    },
    {
      "addr": 18446744071582063173,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582079791,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582196542,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
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
      "addr": 18446744071582023495,
      "name": "ext4_inode_journal_mode.part.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
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
  "name": "ext4_inode_journal_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582035470,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582067845,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582081619,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582087704,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582103932,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582118044,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582173457,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    },
    {
      "addr": 18446744071582212779,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582229381,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582345265,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:407",
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
      "addr": 18446744071582173652,
      "name": "ext4_inode_journal_mode.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582223635,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582255952,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582269909,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582275852,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582292300,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582305554,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582362433,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    },
    {
      "addr": 18446744071582402869,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582419259,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582534465,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
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
      "addr": 18446744071582317520,
      "name": "ext4_inode_journal_mode.part.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582318531,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582351712,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582368570,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374423,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582391052,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582404178,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582461441,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    },
    {
      "addr": 18446744071582501819,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582518732,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582635569,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
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
      "addr": 18446744071582416320,
      "name": "ext4_inode_journal_mode.part.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582485603,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582521024,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582536801,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582542789,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582560011,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570284,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582630494,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    },
    {
      "addr": 18446744071582672978,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582687449,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582808196,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
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
      "addr": 18446744071582584992,
      "name": "ext4_inode_journal_mode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582584867,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582620784,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582637969,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582643733,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582660955,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582671244,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582731630,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    },
    {
      "addr": 18446744071582774995,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582789641,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582911556,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
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
      "addr": 18446744071582685904,
      "name": "ext4_inode_journal_mode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
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
int ext4_inode_journal_mode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582892976,
      "name": "ext4_inode_journal_mode",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:10",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_one_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_quota_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582892976,
      "name": "ext4_inode_journal_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int ext4_inode_journal_mode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582965328,
      "name": "ext4_inode_journal_mode",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:10",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_one_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_journal_finish_inode_data_buffers",
        "fs/ext4/super.c:ext4_journal_submit_inode_data_buffers",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582965328,
      "name": "ext4_inode_journal_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int ext4_inode_journal_mode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582991232,
      "name": "ext4_inode_journal_mode",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:10",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_one_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_journal_finish_inode_data_buffers",
        "fs/ext4/super.c:ext4_journal_submit_inode_data_buffers",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582991232,
      "name": "ext4_inode_journal_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int ext4_inode_journal_mode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583327424,
      "name": "ext4_inode_journal_mode",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:10",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_journal_finish_inode_data_buffers",
        "fs/ext4/super.c:ext4_journal_submit_inode_data_buffers",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583327424,
      "name": "ext4_inode_journal_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int ext4_inode_journal_mode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583835728,
      "name": "ext4_inode_journal_mode",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:10",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/file.c:ext4_dio_supported",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_one_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_journal_finish_inode_data_buffers",
        "fs/ext4/super.c:ext4_journal_submit_inode_data_buffers",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583835728,
      "name": "ext4_inode_journal_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int ext4_inode_journal_mode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584458976,
      "name": "ext4_inode_journal_mode",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:10",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_dio_alignment",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:mpage_map_one_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_quota_on",
        "fs/ext4/super.c:ext4_journal_finish_inode_data_buffers",
        "fs/ext4/super.c:ext4_journal_submit_inode_data_buffers",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584458976,
      "name": "ext4_inode_journal_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int ext4_inode_journal_mode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584687872,
      "name": "ext4_inode_journal_mode",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:10",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_dio_alignment",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_one_extent",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_journal_finish_inode_data_buffers",
        "fs/ext4/super.c:ext4_journal_submit_inode_data_buffers",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584687872,
      "name": "ext4_inode_journal_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int ext4_inode_journal_mode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584920608,
      "name": "ext4_inode_journal_mode",
      "external": true,
      "loc": "fs/ext4/ext4_jbd2.c:10",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_dio_alignment",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_one_extent",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_journal_finish_inode_data_buffers",
        "fs/ext4/super.c:ext4_journal_submit_inode_data_buffers",
        "fs/ext4/fast_commit.c:ext4_fc_track_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584920608,
      "name": "ext4_inode_journal_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int ext4_inode_journal_mode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494234408,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494270064,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494290156,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494295636,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494313424,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494323744,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494388500,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    },
    {
      "addr": 18446603336494441372,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494459104,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494587852,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
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
      "addr": 18446603336494339896,
      "name": "ext4_inode_journal_mode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    },
    {
      "addr": 18446603336494339904,
      "name": "ext4_inode_journal_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227664716,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 3227703876,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 3227722520,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 3227729428,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 3227749076,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 3227759372,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 3227826648,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    },
    {
      "addr": 3227877656,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 3227894348,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 3228030532,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
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
      "addr": 3227775836,
      "name": "ext4_inode_journal_mode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287934300,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287980084,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288004040,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288010772,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288033376,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288047884,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288128824,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    },
    {
      "addr": 13835058055288193644,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288213764,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288387072,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
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
      "addr": 13835058055288069872,
      "name": "ext4_inode_journal_mode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273687348,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273718144,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273733462,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273737820,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273752768,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273762716,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273812916,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    },
    {
      "addr": 18446743936273854050,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273866772,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273966416,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
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
      "addr": 18446743936273773550,
      "name": "ext4_inode_journal_mode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582553603,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582589520,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582606705,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582612469,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582629691,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582639980,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582700366,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    },
    {
      "addr": 18446744071582743731,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582758377,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582880292,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
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
      "addr": 18446744071582654640,
      "name": "ext4_inode_journal_mode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582490771,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582526688,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582543873,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582549637,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582566859,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582577148,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582637534,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    },
    {
      "addr": 18446744071582680899,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582695545,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582817444,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
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
      "addr": 18446744071582591808,
      "name": "ext4_inode_journal_mode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582543715,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582579632,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582596817,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582602581,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582619547,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582629836,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582690222,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    },
    {
      "addr": 18446744071582733587,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582748233,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582869172,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
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
      "addr": 18446744071582644496,
      "name": "ext4_inode_journal_mode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_inode_journal_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582624830,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/ext4_jbd2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ext4_jbd2.c:__ext4_forget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582661104,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582678881,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582684809,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582701707,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_clear_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582713068,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582774526,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_set_inode_flags",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    },
    {
      "addr": 18446744071582818697,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582833513,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582955876,
      "name": "ext4_inode_journal_mode",
      "external": false,
      "loc": "fs/ext4/ext4_jbd2.h:404",
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
      "addr": 18446744071582728144,
      "name": "ext4_inode_journal_mode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ext4_inode_journal_mode(struct inode * inode)
```
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int ext4_inode_journal_mode(struct inode * inode)
```
</details>
</li>
</ul>
