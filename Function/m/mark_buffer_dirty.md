# Function: <code>mark_buffer_dirty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581215216,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1158",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:mark_buffer_dirty_inode",
        "fs/buffer.c:__block_write_begin",
        "fs/buffer.c:block_truncate_page",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581215216,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581379872,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1149",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:mark_buffer_dirty_inode",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379872,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581458000,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1149",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:mark_buffer_dirty_inode",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581458000,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581514256,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1146",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:mark_buffer_dirty_inode",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581514256,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581656512,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1106",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:mark_buffer_dirty_inode",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581656512,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581819296,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1077",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581819296,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581906288,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1085",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581906288,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582043248,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1086",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582043248,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582121824,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1086",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582121824,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582359456,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1112",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:page_zero_new_buffers",
        "fs/buffer.c:mark_buffer_dirty_inode",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582359456,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582417104,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1111",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:page_zero_new_buffers",
        "fs/buffer.c:mark_buffer_dirty_inode",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582417104,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582444432,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1107",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:page_zero_new_buffers",
        "fs/buffer.c:mark_buffer_dirty_inode",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582444432,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582762704,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1082",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:mark_buffer_dirty_inode",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582762704,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583327104,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1079",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:mark_buffer_dirty_inode",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/resize.c:update_backups",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583327104,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583913056,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1079",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:mark_buffer_dirty_inode",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/resize.c:update_backups",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583913056,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584121552,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1191",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:folio_zero_new_buffers",
        "fs/buffer.c:mark_buffer_dirty_inode",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/resize.c:update_backups",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584121552,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584338048,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1174",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_commit_write",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:folio_zero_new_buffers",
        "fs/buffer.c:mark_buffer_dirty_inode",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/resize.c:update_backups",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584338048,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493664800,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1086",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493664800,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227195664,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1086",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:mark_buffer_dirty_inode",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227195664,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287259760,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1086",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:mark_buffer_dirty_inode",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287259760,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273290760,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1086",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273290760,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582090560,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1086",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582090560,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582028080,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1086",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582028080,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582081040,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1086",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582081040,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void mark_buffer_dirty(struct buffer_head * bh)
```

```json
{
  "name": "mark_buffer_dirty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582154016,
      "name": "mark_buffer_dirty",
      "external": true,
      "loc": "fs/buffer.c:1086",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582154016,
      "name": "mark_buffer_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
