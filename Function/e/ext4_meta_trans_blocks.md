# Function: <code>ext4_meta_trans_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581556512,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:4938",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581556512,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581742320,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5279",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742320,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581830016,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5423",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581830016,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581978144,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5583",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581978144,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582127904,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5636",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582127904,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582316416,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5732",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582316416,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582415200,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5784",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582415200,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582583904,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5806",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583904,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582684704,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5820",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582684704,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582997120,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5541",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_alloc",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582997120,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583073488,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5632",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_alloc",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583073488,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583100000,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5629",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583100000,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583440688,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5568",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583440688,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583958656,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5646",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583958656,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584586560,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5785",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584586560,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584813280,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5597",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584813280,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585044368,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5617",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_do_writepages",
        "fs/ext4/inode.c:ext4_do_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585044368,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494339248,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5820",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494339248,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227774416,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5820",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227774416,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288066336,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5820",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288066336,
      "name": "ext4_meta_trans_blocks",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273772364,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5820",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273772364,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582653440,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5820",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582653440,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582590608,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5820",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582590608,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582643296,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5820",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582643296,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
int ext4_meta_trans_blocks(struct inode * inode, int lblocks, int pextents)
```

```json
{
  "name": "ext4_meta_trans_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582726912,
      "name": "ext4_meta_trans_blocks",
      "external": false,
      "loc": "fs/ext4/inode.c:5820",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage_trans_blocks",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_get_block_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582726912,
      "name": "ext4_meta_trans_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
