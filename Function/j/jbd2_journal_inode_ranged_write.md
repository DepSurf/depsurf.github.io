# Function: <code>jbd2_journal_inode_ranged_write</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t * handle, struct jbd2_inode * jinode, loff_t start_byte, loff_t length)
```

```json
{
  "name": "jbd2_journal_inode_ranged_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582876336,
      "name": "jbd2_journal_inode_ranged_write",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2634",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582876336,
      "name": "jbd2_journal_inode_ranged_write",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t * handle, struct jbd2_inode * jinode, loff_t start_byte, loff_t length)
```

```json
{
  "name": "jbd2_journal_inode_ranged_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582982960,
      "name": "jbd2_journal_inode_ranged_write",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2631",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582982960,
      "name": "jbd2_journal_inode_ranged_write",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t * handle, struct jbd2_inode * jinode, loff_t start_byte, loff_t length)
```

```json
{
  "name": "jbd2_journal_inode_ranged_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583299248,
      "name": "jbd2_journal_inode_ranged_write",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2699",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583299248,
      "name": "jbd2_journal_inode_ranged_write",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t * handle, struct jbd2_inode * jinode, loff_t start_byte, loff_t length)
```

```json
{
  "name": "jbd2_journal_inode_ranged_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583414544,
      "name": "jbd2_journal_inode_ranged_write",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2697",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583414544,
      "name": "jbd2_journal_inode_ranged_write",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t * handle, struct jbd2_inode * jinode, loff_t start_byte, loff_t length)
```

```json
{
  "name": "jbd2_journal_inode_ranged_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583437392,
      "name": "jbd2_journal_inode_ranged_write",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2702",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583437392,
      "name": "jbd2_journal_inode_ranged_write",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t * handle, struct jbd2_inode * jinode, loff_t start_byte, loff_t length)
```

```json
{
  "name": "jbd2_journal_inode_ranged_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583786816,
      "name": "jbd2_journal_inode_ranged_write",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2702",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583786816,
      "name": "jbd2_journal_inode_ranged_write",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t * handle, struct jbd2_inode * jinode, loff_t start_byte, loff_t length)
```

```json
{
  "name": "jbd2_journal_inode_ranged_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584350528,
      "name": "jbd2_journal_inode_ranged_write",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2720",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584350528,
      "name": "jbd2_journal_inode_ranged_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int jbd2_journal_inode_ranged_write(handle_t * handle, struct jbd2_inode * jinode, loff_t start_byte, loff_t length)
```

```json
{
  "name": "jbd2_journal_inode_ranged_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585000544,
      "name": "jbd2_journal_inode_ranged_write",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2728",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585000544,
      "name": "jbd2_journal_inode_ranged_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int jbd2_journal_inode_ranged_write(handle_t * handle, struct jbd2_inode * jinode, loff_t start_byte, loff_t length)
```

```json
{
  "name": "jbd2_journal_inode_ranged_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585228480,
      "name": "jbd2_journal_inode_ranged_write",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2707",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journal_folio_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585228480,
      "name": "jbd2_journal_inode_ranged_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int jbd2_journal_inode_ranged_write(handle_t * handle, struct jbd2_inode * jinode, loff_t start_byte, loff_t length)
```

```json
{
  "name": "jbd2_journal_inode_ranged_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585461472,
      "name": "jbd2_journal_inode_ranged_write",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2717",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journal_folio_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585461472,
      "name": "jbd2_journal_inode_ranged_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int jbd2_journal_inode_ranged_write(handle_t * handle, struct jbd2_inode * jinode, loff_t start_byte, loff_t length)
```

```json
{
  "name": "jbd2_journal_inode_ranged_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494664464,
      "name": "jbd2_journal_inode_ranged_write",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2631",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494664464,
      "name": "jbd2_journal_inode_ranged_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int jbd2_journal_inode_ranged_write(handle_t * handle, struct jbd2_inode * jinode, loff_t start_byte, loff_t length)
```

```json
{
  "name": "jbd2_journal_inode_ranged_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228107732,
      "name": "jbd2_journal_inode_ranged_write",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2631",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228107732,
      "name": "jbd2_journal_inode_ranged_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int jbd2_journal_inode_ranged_write(handle_t * handle, struct jbd2_inode * jinode, loff_t start_byte, loff_t length)
```

```json
{
  "name": "jbd2_journal_inode_ranged_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288480304,
      "name": "jbd2_journal_inode_ranged_write",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2631",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288480304,
      "name": "jbd2_journal_inode_ranged_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int jbd2_journal_inode_ranged_write(handle_t * handle, struct jbd2_inode * jinode, loff_t start_byte, loff_t length)
```

```json
{
  "name": "jbd2_journal_inode_ranged_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274027568,
      "name": "jbd2_journal_inode_ranged_write",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2631",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274027568,
      "name": "jbd2_journal_inode_ranged_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int jbd2_journal_inode_ranged_write(handle_t * handle, struct jbd2_inode * jinode, loff_t start_byte, loff_t length)
```

```json
{
  "name": "jbd2_journal_inode_ranged_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582951696,
      "name": "jbd2_journal_inode_ranged_write",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2631",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582951696,
      "name": "jbd2_journal_inode_ranged_write",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t * handle, struct jbd2_inode * jinode, loff_t start_byte, loff_t length)
```

```json
{
  "name": "jbd2_journal_inode_ranged_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582888848,
      "name": "jbd2_journal_inode_ranged_write",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2631",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582888848,
      "name": "jbd2_journal_inode_ranged_write",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t * handle, struct jbd2_inode * jinode, loff_t start_byte, loff_t length)
```

```json
{
  "name": "jbd2_journal_inode_ranged_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582940304,
      "name": "jbd2_journal_inode_ranged_write",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2631",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582940304,
      "name": "jbd2_journal_inode_ranged_write",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t * handle, struct jbd2_inode * jinode, loff_t start_byte, loff_t length)
```

```json
{
  "name": "jbd2_journal_inode_ranged_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583028400,
      "name": "jbd2_journal_inode_ranged_write",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2631",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583028400,
      "name": "jbd2_journal_inode_ranged_write",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t * handle, struct jbd2_inode * jinode, loff_t start_byte, loff_t length)
```
</details>
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
