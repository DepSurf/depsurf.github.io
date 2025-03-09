# Function: <code>alloc_page_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, int retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581218736,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:872",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:nobh_write_begin",
        "drivers/md/bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581218736,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, int retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581382816,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:865",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "drivers/md/bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581382816,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, int retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581460960,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:866",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp",
        "drivers/md/bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581460960,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, int retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581516640,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:863",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp",
        "drivers/md/bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581516640,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581658688,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:842",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581658688,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581821296,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:812",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581821296,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581908464,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:813",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581908464,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582045456,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:814",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582045456,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582123232,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:814",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123232,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582357824,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:840",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:grow_dev_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582357824,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582415392,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:839",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:grow_dev_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582415392,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582443040,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:839",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:grow_dev_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582443040,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582767280,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:814",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:grow_dev_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582767280,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583319200,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:811",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:grow_dev_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583319200,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583905552,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:811",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:grow_dev_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583905552,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584129872,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:972",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584129872,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584346720,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:956",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584346720,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493666640,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:814",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493666640,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227197116,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:814",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_slow",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227197116,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287263552,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:814",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287263552,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273292490,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:814",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273292490,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582091968,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:814",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582091968,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582029488,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:814",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582029488,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582082448,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:814",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582082448,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
struct buffer_head * alloc_page_buffers(struct page * page, long unsigned int size, bool retry)
```

```json
{
  "name": "alloc_page_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582155648,
      "name": "alloc_page_buffers",
      "external": true,
      "loc": "fs/buffer.c:814",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582155648,
      "name": "alloc_page_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int retry</code> ➡️ <code>bool retry</code>
</li>
</ul>
</details>
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
