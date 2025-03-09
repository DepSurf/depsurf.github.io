# Function: <code>_ext4_get_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581568752,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:691",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_write",
        "fs/ext4/inode.c:ext4_get_block_write_nolock",
        "fs/ext4/inode.c:ext4_get_block_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581568752,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581753872,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:743",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581753872,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581842016,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:754",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581842016,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581991680,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:760",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581991680,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582141216,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:770",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_dio_get_block_overwrite",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141216,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582330208,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:771",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_dio_get_block_overwrite",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582330208,
      "name": "_ext4_get_block",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582428816,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:771",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_dio_get_block_overwrite",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582428816,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582598080,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:779",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582598080,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582698816,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:788",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582698816,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583010736,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:767",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583010736,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583086208,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:781",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583086208,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583111216,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:782",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583111216,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:782",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583450832,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071592258493,
      "name": "_ext4_get_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:790",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972528,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071594039733,
      "name": "_ext4_get_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:796",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584600512,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071596072735,
      "name": "_ext4_get_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:751",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584826736,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    },
    {
      "addr": 18446744071596596237,
      "name": "_ext4_get_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:753",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585059712,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    },
    {
      "addr": 18446744071597501756,
      "name": "_ext4_get_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494355568,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:788",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494355568,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227788844,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:788",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227788844,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288085296,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:788",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288085296,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273785186,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:788",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273785186,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582667552,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:788",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582667552,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582604720,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:788",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582604720,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582657408,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:788",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582657408,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
int _ext4_get_block(struct inode * inode, sector_t iblock, struct buffer_head * bh, int flags)
```

```json
{
  "name": "_ext4_get_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582741088,
      "name": "_ext4_get_block",
      "external": false,
      "loc": "fs/ext4/inode.c:788",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_get_block_trans",
        "fs/ext4/inode.c:ext4_get_block_unwritten"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582741088,
      "name": "_ext4_get_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
