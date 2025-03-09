# Function: <code>clean_bdev_aliases</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581462016,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1628",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581462016,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581517696,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1623",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517696,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581659888,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1583",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581659888,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581822576,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1554",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581822576,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581909488,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1562",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581909488,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 506
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582046272,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1563",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582046272,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582124048,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1563",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124048,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582358160,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1607",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582358160,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582415808,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1606",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582415808,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582442448,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1626",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582442448,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1605",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592231896,
      "name": "clean_bdev_aliases.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071582764960,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1603",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594012156,
      "name": "clean_bdev_aliases.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071583317360,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1588",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596052253,
      "name": "clean_bdev_aliases.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071583901520,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1721",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_folio",
        "fs/mpage.c:__mpage_writepage",
        "fs/direct-io.c:do_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596574810,
      "name": "clean_bdev_aliases.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071584125024,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1697",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_folio",
        "fs/mpage.c:__mpage_writepage",
        "fs/direct-io.c:do_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597479428,
      "name": "clean_bdev_aliases.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071584341136,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493660880,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1563",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493660880,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227198532,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1563",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227198532,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287266496,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1563",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287266496,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273293562,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1563",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273293562,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582092784,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1563",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582092784,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582030304,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1563",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582030304,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582083264,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1563",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582083264,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```

```json
{
  "name": "clean_bdev_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582156816,
      "name": "clean_bdev_aliases",
      "external": true,
      "loc": "fs/buffer.c:1563",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582156816,
      "name": "clean_bdev_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void clean_bdev_aliases(struct block_device * bdev, sector_t block, sector_t len)
```
</details>
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
