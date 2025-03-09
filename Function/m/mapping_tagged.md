# Function: <code>mapping_tagged</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mapping_tagged(struct address_space * mapping, int tag)
```

```json
{
  "name": "mapping_tagged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580518720,
      "name": "mapping_tagged",
      "external": true,
      "loc": "mm/page-writeback.c:2798",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580518720,
      "name": "mapping_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mapping_tagged(struct address_space * mapping, int tag)
```

```json
{
  "name": "mapping_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580605802,
      "name": "mapping_tagged",
      "external": true,
      "loc": "mm/page-writeback.c:2858",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580604832,
      "name": "mapping_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mapping_tagged(struct address_space * mapping, int tag)
```

```json
{
  "name": "mapping_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580672914,
      "name": "mapping_tagged",
      "external": true,
      "loc": "mm/page-writeback.c:2825",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580671744,
      "name": "mapping_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mapping_tagged(struct address_space * mapping, int tag)
```

```json
{
  "name": "mapping_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580710785,
      "name": "mapping_tagged",
      "external": true,
      "loc": "mm/page-writeback.c:2834",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580704944,
      "name": "mapping_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mapping_tagged(struct address_space * mapping, int tag)
```

```json
{
  "name": "mapping_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580796354,
      "name": "mapping_tagged",
      "external": true,
      "loc": "mm/page-writeback.c:2817",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580790464,
      "name": "mapping_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int mapping_tagged(struct address_space * mapping, int tag)
```

```json
{
  "name": "mapping_tagged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580936439,
      "name": "mapping_tagged",
      "external": true,
      "loc": "mm/page-writeback.c:2814",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580925808,
      "name": "mapping_tagged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
  "name": "mapping_tagged",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581004097,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:500",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581864573,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:500",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582446466,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:500",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "mapping_tagged",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581068384,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:512",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581989349,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:512",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582615764,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:512",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "mapping_tagged",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581097948,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581124352,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582075140,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582716772,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "mapping_tagged",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581274390,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:522",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581311004,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:522",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582300762,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:522",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wait_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583027136,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:522",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mapping_tagged",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581321126,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:486",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581357944,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:486",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353786,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:486",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wait_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583102765,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:486",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mapping_tagged",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581326296,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:487",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_range_needs_writeback",
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581377146,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:487",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582380922,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:487",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wait_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583128237,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:487",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mapping_tagged",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581572757,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:494",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_range_needs_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626125,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:494",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582703498,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:494",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wait_sb_inodes",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:inode_do_switch_wbs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583469513,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:494",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mapping_tagged",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581948001,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:444",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581987048,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:444",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:__folio_end_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583256841,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:444",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:inode_do_switch_wbs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583618862,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:444",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:__iomap_dio_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583993243,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:444",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585599058,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:444",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_read_iter"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mapping_tagged",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582381851,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:459",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582423055,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:459",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:__folio_end_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583838537,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:459",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:inode_do_switch_wbs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584221611,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:459",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:__iomap_dio_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584622763,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:459",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_do_writepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586366850,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:459",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_read_iter"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mapping_tagged",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582589267,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:474",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:kiocb_write_and_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582628268,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:474",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:__folio_end_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584056617,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:474",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:inode_do_switch_wbs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584847009,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:474",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_do_writepages"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mapping_tagged",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582753251,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:507",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:kiocb_write_and_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582794747,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:507",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:__folio_end_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584271529,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:507",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fs-writeback.c:inode_do_switch_wbs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585079841,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:507",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_do_writepages"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "mapping_tagged",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492462540,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492499076,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493606740,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494374088,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "mapping_tagged",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226338344,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226366004,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 3227151660,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 3227810320,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "mapping_tagged",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285742908,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285782880,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287193880,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288108880,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "mapping_tagged",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272533832,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272556610,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273254680,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273800772,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "mapping_tagged",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581066796,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581093200,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582043876,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582685508,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "mapping_tagged",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581013996,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040362,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581981444,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582622676,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "mapping_tagged",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581057996,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581084400,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582035156,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582675364,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "mapping_tagged",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581119580,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_fdatawrite_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146320,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582106638,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:writeback_sb_inodes",
        "fs/fs-writeback.c:writeback_single_inode",
        "fs/fs-writeback.c:__writeback_single_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582759348,
      "name": "mapping_tagged",
      "external": false,
      "loc": "include/linux/fs.h:519",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_writepages"
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int mapping_tagged(struct address_space * mapping, int tag)
```
</details>
</li>
</ul>
