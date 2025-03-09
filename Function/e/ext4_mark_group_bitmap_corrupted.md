# Function: <code>ext4_mark_group_bitmap_corrupted</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582544048,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:777",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582544048,
      "name": "ext4_mark_group_bitmap_corrupted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582645184,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:819",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582645184,
      "name": "ext4_mark_group_bitmap_corrupted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582817968,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:830",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582817968,
      "name": "ext4_mark_group_bitmap_corrupted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582921136,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:825",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582921136,
      "name": "ext4_mark_group_bitmap_corrupted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583237968,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:853",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583237968,
      "name": "ext4_mark_group_bitmap_corrupted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583339744,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:1009",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583339744,
      "name": "ext4_mark_group_bitmap_corrupted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583362640,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:1018",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583362640,
      "name": "ext4_mark_group_bitmap_corrupted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:1017",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592271110,
      "name": "ext4_mark_group_bitmap_corrupted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071583705488,
      "name": "ext4_mark_group_bitmap_corrupted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:1049",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594052764,
      "name": "ext4_mark_group_bitmap_corrupted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071584259520,
      "name": "ext4_mark_group_bitmap_corrupted",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:1042",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_wait_block_bitmap",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596084214,
      "name": "ext4_mark_group_bitmap_corrupted.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071584909056,
      "name": "ext4_mark_group_bitmap_corrupted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585137920,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:1042",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_wait_block_bitmap",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585137920,
      "name": "ext4_mark_group_bitmap_corrupted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585370704,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:1111",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_wait_block_bitmap",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585370704,
      "name": "ext4_mark_group_bitmap_corrupted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494597896,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:825",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494597896,
      "name": "ext4_mark_group_bitmap_corrupted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228040580,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:825",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228040580,
      "name": "ext4_mark_group_bitmap_corrupted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288398992,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:825",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288398992,
      "name": "ext4_mark_group_bitmap_corrupted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273974346,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:825",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273974346,
      "name": "ext4_mark_group_bitmap_corrupted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582889872,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:825",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582889872,
      "name": "ext4_mark_group_bitmap_corrupted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582827024,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:825",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582827024,
      "name": "ext4_mark_group_bitmap_corrupted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582878768,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:825",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582878768,
      "name": "ext4_mark_group_bitmap_corrupted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```

```json
{
  "name": "ext4_mark_group_bitmap_corrupted",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582965488,
      "name": "ext4_mark_group_bitmap_corrupted",
      "external": true,
      "loc": "fs/ext4/super.c:825",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_complex_scan_group",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582965488,
      "name": "ext4_mark_group_bitmap_corrupted",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void ext4_mark_group_bitmap_corrupted(struct super_block * sb, ext4_group_t group, unsigned int flags)
```
</details>
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
