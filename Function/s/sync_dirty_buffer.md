# Function: <code>sync_dirty_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581231392,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3153",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581231392,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581399168,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3212",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581399168,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581477504,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3253",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581477504,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581532528,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3240",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581532528,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581675136,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3208",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581675136,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581838704,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3179",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581838704,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581925968,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3191",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581925968,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582063392,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3198",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582063392,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582141248,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3175",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141248,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582374224,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3185",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582374224,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582430528,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3166",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582430528,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582457312,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3187",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582457312,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582780928,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3166",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582780928,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583333024,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3151",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583333024,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583917552,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:2756",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583917552,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584140128,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:2894",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140128,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584356304,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:2854",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/ioctl.c:ext4_update_primary_sb",
        "fs/ext4/mballoc.c:ext4_mb_mark_context",
        "fs/ext4/mballoc.c:ext4_mb_mark_context",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename_exchange",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584356304,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493687128,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3175",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493687128,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227219164,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3175",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227219164,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287291392,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3175",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287291392,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273309502,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3175",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273309502,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582109984,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3175",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582109984,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582047424,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3175",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582047424,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582100464,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3175",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582100464,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int sync_dirty_buffer(struct buffer_head * bh)
```

```json
{
  "name": "sync_dirty_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582173344,
      "name": "sync_dirty_buffer",
      "external": true,
      "loc": "fs/buffer.c:3175",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/ext4/inode.c:ext4_write_inode",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582173344,
      "name": "sync_dirty_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
