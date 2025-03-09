# Function: <code>__block_write_full_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581231568,
      "name": "__block_write_full_page",
      "external": false,
      "loc": "fs/buffer.c:1701",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581231568,
      "name": "__block_write_full_page.constprop.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 928
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581389008,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1691",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581389008,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 876
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581467440,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1734",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581467440,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581522960,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1729",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522960,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 974
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581665280,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1689",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581665280,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1005
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581828592,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1660",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828592,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1077
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581915840,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1668",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915840,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1083
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1669",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582063904,
      "name": "__block_write_full_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071582053008,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1070
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582130672,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1669",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582130672,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1091
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582368848,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1713",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582368848,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1139
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582427344,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1712",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582427344,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1170
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582449632,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1732",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449632,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1174
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1711",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592232271,
      "name": "__block_write_full_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071582772064,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1170
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1709",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594013157,
      "name": "__block_write_full_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071583330992,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1325
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1694",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_write_full_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596053058,
      "name": "__block_write_full_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071583915760,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1290
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493674360,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1669",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493674360,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1576
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227206400,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1669",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227206400,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1580
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287276032,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1669",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287276032,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1648
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273299760,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1669",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273299760,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1008
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582099408,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1669",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582099408,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1091
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582036848,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1669",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582036848,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1091
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582089888,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1669",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582089888,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1091
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```

```json
{
  "name": "__block_write_full_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582162624,
      "name": "__block_write_full_page",
      "external": true,
      "loc": "fs/buffer.c:1669",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582162624,
      "name": "__block_write_full_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1067
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
```
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
int __block_write_full_page(struct inode * inode, struct page * page, get_block_t * get_block, struct writeback_control * wbc, bh_end_io_t * handler)
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
