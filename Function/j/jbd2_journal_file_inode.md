# Function: <code>jbd2_journal_file_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581898416,
      "name": "jbd2_journal_file_inode",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2479",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581898416,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582077280,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2464",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_add_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_add_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582077280,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582167392,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2469",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_add_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_add_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582167392,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582253968,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2487",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_add_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_add_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582253968,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582402976,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2490",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_add_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_add_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582402976,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582593296,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2493",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_add_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_add_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582593296,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582694960,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2533",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_add_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_add_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582694960,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582867584,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2567",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write",
        "fs/jbd2/transaction.c:jbd2_journal_inode_add_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_add_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582867584,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582974128,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2576",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974128,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583291280,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2644",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583291280,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583406816,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2642",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583406816,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583429536,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2647",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583429536,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583778896,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2647",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583778896,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584337472,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2665",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584337472,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584986640,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2673",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584986640,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585214672,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2652",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585214672,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585447632,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2662",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585447632,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494648336,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2576",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494648336,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228091796,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2576",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228091796,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288460240,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2576",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288460240,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274017946,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2576",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274017946,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582942864,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2576",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582942864,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582880016,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2576",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880016,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582931472,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2576",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582931472,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
int jbd2_journal_file_inode(handle_t * handle, struct jbd2_inode * jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "jbd2_journal_file_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583015552,
      "name": "jbd2_journal_file_inode",
      "external": false,
      "loc": "fs/jbd2/transaction.c:2576",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait",
        "fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583015552,
      "name": "jbd2_journal_file_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
<code>long unsigned int flags</code>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>loff_t start_byte</code>
</li>
<li>
<b>Param added. </b>
<code>loff_t end_byte</code>
</li>
</ul>
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
