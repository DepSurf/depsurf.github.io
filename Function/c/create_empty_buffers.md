# Function: <code>create_empty_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581218960,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1588",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581218960,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581383040,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1578",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581383040,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581461184,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1578",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581461184,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581518256,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1573",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:create_page_buffers",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518256,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581658880,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1533",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:create_page_buffers",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581658880,
      "name": "create_empty_buffers",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581823936,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1504",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:create_page_buffers",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581823936,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581911248,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1512",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:create_page_buffers",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911248,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582048368,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1513",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:create_page_buffers",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582048368,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582126224,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1513",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126224,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582362480,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1557",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:create_page_buffers",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582362480,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582419376,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1556",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:create_page_buffers",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582419376,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582449264,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1576",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:create_page_buffers",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449264,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582771664,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1555",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:create_page_buffers",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582771664,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583323008,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1553",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:create_page_buffers",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583323008,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583910912,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1538",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:create_page_buffers",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583910912,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584129728,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1694",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584129728,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
struct buffer_head * create_empty_buffers(struct folio * folio, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584345328,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1644",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584345328,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493667072,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1513",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:create_page_buffers",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493667072,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227197592,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1513",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:create_page_buffers",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227197592,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287264112,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1513",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:create_page_buffers",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287264112,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273295380,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1513",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:create_page_buffers",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273295380,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582094960,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1513",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582094960,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582032432,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1513",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582032432,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582085440,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1513",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582085440,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void create_empty_buffers(struct page * page, long unsigned int blocksize, long unsigned int b_state)
```

```json
{
  "name": "create_empty_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582156016,
      "name": "create_empty_buffers",
      "external": true,
      "loc": "fs/buffer.c:1513",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_truncate_page",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582156016,
      "name": "create_empty_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>struct buffer_head *</code>
</li>
</ul>
</details>
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
