# Function: <code>create_page_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581219360,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1663",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581219360,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581383312,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1653",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581383312,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581461456,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1696",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581461456,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581518496,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1691",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518496,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581659120,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1650",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581659120,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581824208,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1621",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824208,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581911520,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1629",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911520,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582048640,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1630",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582048640,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582126496,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1630",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126496,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582362752,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1674",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582362752,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582419648,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1673",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582419648,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582449536,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1693",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449536,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1672",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582771936,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071592232239,
      "name": "create_page_buffers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1670",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583323600,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071594012513,
      "name": "create_page_buffers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1655",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583911520,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071596052756,
      "name": "create_page_buffers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493667584,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1630",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493667584,
      "name": "create_page_buffers",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227198000,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1630",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227198000,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287264752,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1630",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287264752,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273295730,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1630",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273295730,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582095232,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1630",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582095232,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582032704,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1630",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582032704,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582085712,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1630",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582085712,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```

```json
{
  "name": "create_page_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582156288,
      "name": "create_page_buffers",
      "external": false,
      "loc": "fs/buffer.c:1630",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582156288,
      "name": "create_page_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
struct buffer_head * create_page_buffers(struct page * page, struct inode * inode, unsigned int b_state)
```
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
