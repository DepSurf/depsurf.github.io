# Function: <code>mark_buffer_dirty_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581215504,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:603",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581215504,
      "name": "mark_buffer_dirty_inode",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581380144,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:597",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581380144,
      "name": "mark_buffer_dirty_inode",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581458272,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:598",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581458272,
      "name": "mark_buffer_dirty_inode",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581514496,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:595",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581514496,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581656752,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:574",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581656752,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581824560,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:543",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824560,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581907344,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:544",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581907344,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582044288,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:545",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582044288,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582122064,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:545",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582122064,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582359696,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:571",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582359696,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582417328,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:570",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582417328,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582444656,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:570",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582444656,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582778176,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:570",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582778176,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583327488,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:570",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583327488,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583913456,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:570",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
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
      "addr": 18446744071583913456,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584121824,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:681",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
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
      "addr": 18446744071584121824,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584338320,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:669",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
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
      "addr": 18446744071584338320,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493665232,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:545",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493665232,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227196040,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:545",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227196040,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287260304,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:545",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287260304,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273291058,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:545",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/fatent.c:fat12_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273291058,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582090800,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:545",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582090800,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582028320,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:545",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582028320,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582081280,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:545",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582081280,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void mark_buffer_dirty_inode(struct buffer_head * bh, struct inode * inode)
```

```json
{
  "name": "mark_buffer_dirty_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582154288,
      "name": "mark_buffer_dirty_inode",
      "external": true,
      "loc": "fs/buffer.c:545",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries",
        "fs/fat/dir.c:__fat_remove_entries",
        "fs/fat/fatent.c:fat_mirror_bhs",
        "fs/fat/fatent.c:fat32_ent_put",
        "fs/fat/fatent.c:fat16_ent_put",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582154288,
      "name": "mark_buffer_dirty_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
