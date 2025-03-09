# Function: <code>mb_free_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793504,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1417",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_free_data_callback",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793504,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1456
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989040,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1426",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_free_data_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989040,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1449
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582079264,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1426",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_free_data_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582079264,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1448
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582043344,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1424",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582043344,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1485
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582193968,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1424",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582193968,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1485
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582383952,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1413",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582383952,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1568
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582483088,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1413",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582483088,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1568
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1413",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582652608,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1475
    },
    {
      "addr": 18446744071582677314,
      "name": "mb_free_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582754608,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1413",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582754608,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1482
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583065264,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1474",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_extent",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583065264,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1021
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583130320,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1443",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_extent",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583130320,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583157232,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1777",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_data_in_buddy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583157232,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1781",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583500544,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
    },
    {
      "addr": 18446744071592260946,
      "name": "mb_free_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1778",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_discard_allocated_blocks",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584030176,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1133
    },
    {
      "addr": 18446744071594043365,
      "name": "mb_free_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1735",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_discard_allocated_blocks",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584664032,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1164
    },
    {
      "addr": 18446744071596076701,
      "name": "mb_free_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1875",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_discard_allocated_blocks",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584887920,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1155
    },
    {
      "addr": 18446744071596600568,
      "name": "mb_free_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1891",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_release_inode_pa",
        "fs/ext4/mballoc.c:ext4_discard_allocated_blocks",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585131984,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1308
    },
    {
      "addr": 18446744071597506925,
      "name": "mb_free_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494419688,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1413",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494419688,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1696
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227852860,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1413",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_release_inode_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227852860,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1788
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288162768,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1413",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288162768,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2368
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273833220,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1413",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273833220,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1422
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582723344,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1413",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582723344,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1482
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582660512,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1413",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582660512,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1482
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582713200,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1413",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582713200,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1482
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
void mb_free_blocks(struct inode * inode, struct ext4_buddy * e4b, int first, int count)
```

```json
{
  "name": "mb_free_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582797888,
      "name": "mb_free_blocks",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1413",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582797888,
      "name": "mb_free_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1482
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
