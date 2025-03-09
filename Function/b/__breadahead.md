# Function: <code>__breadahead</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581225120,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1405",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_count_free_clusters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581225120,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581392000,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1395",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_count_free_clusters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581392000,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581470416,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1395",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_count_free_clusters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581470416,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581525952,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1390",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_count_free_clusters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581525952,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668272,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1350",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_count_free_clusters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668272,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831696,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1321",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_count_free_clusters"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831696,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581918944,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1329",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918944,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582056144,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1330",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582056144,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582133920,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1330",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133920,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582367552,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1363",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582367552,
      "name": "__breadahead",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582426336,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1362",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582426336,
      "name": "__breadahead",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582453952,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1367",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582453952,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582780064,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1342",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582780064,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583324800,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1341",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583324800,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583910736,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1341",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583910736,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584139232,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1453",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584139232,
      "name": "__breadahead",
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584355376,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1436",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584355376,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493678736,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1330",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493678736,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227210644,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1330",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_reada"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227210644,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287280800,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1330",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287280800,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273302824,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1330",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273302824,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582102656,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1330",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102656,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582040096,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1330",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582040096,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582093136,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1330",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582093136,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __breadahead(struct block_device * bdev, sector_t block, unsigned int size)
```

```json
{
  "name": "__breadahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582165888,
      "name": "__breadahead",
      "external": true,
      "loc": "fs/buffer.c:1330",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fat/dir.c:fat__get_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582165888,
      "name": "__breadahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
