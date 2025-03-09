# Function: <code>ll_rw_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ll_rw_block(int rw, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581224848,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3086",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:write_boundary_block",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:__block_write_begin",
        "fs/buffer.c:block_truncate_page",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_get_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581224848,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581391712,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3145",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581391712,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581470128,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3186",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581470128,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581525648,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3173",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581525648,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581667968,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3141",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581667968,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831392,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3112",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831392,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581918640,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3124",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918640,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582055856,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3131",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582055856,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582133632,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3108",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133632,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582360112,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3109",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead_gfp",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/journal.c:journal_get_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582360112,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582417744,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3090",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead_gfp",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/jbd2/journal.c:journal_get_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582417744,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582445456,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3111",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead_gfp",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/jbd2/journal.c:journal_get_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582445456,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582768080,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3090",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead_gfp",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/jbd2/journal.c:journal_get_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582768080,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583318016,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3075",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead_gfp",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/jbd2/journal.c:journal_get_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583318016,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493678136,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3108",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493678136,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227210152,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3108",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227210152,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287280192,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3108",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287280192,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273302468,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3108",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273302468,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582102368,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3108",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102368,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582039808,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3108",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582039808,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582092848,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3108",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582092848,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```

```json
{
  "name": "ll_rw_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582165600,
      "name": "ll_rw_block",
      "external": true,
      "loc": "fs/buffer.c:3108",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__breadahead",
        "fs/buffer.c:write_boundary_block",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_bread_batch",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582165600,
      "name": "ll_rw_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int op</code>
</li>
<li>
<b>Param added. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
<li>
<b>Param reordered. </b>
<code>rw, nr, bhs</code> ➡️ <code>op, op_flags, nr, bhs</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head * * bhs)
```
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
