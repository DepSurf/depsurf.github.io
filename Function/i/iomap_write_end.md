# Function: <code>iomap_write_end</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int iomap_write_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581582304,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap.c:137",
      "file": "fs/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582304,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int iomap_write_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581667584,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap.c:138",
      "file": "fs/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_dirty_actor",
        "fs/iomap.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581667584,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int iomap_write_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581721792,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap.c:140",
      "file": "fs/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_dirty_actor",
        "fs/iomap.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581721792,
      "name": "iomap_write_end",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int iomap_write_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581867616,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap.c:140",
      "file": "fs/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_dirty_actor",
        "fs/iomap.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581867616,
      "name": "iomap_write_end",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int iomap_write_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582050144,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap.c:150",
      "file": "fs/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_dirty_actor",
        "fs/iomap.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582050144,
      "name": "iomap_write_end",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int iomap_write_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page, struct iomap * iomap)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582139040,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap.c:768",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_dirty_actor",
        "fs/iomap.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582139040,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
int iomap_write_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page, struct iomap * iomap)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582303056,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:699",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582303056,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 633
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
int iomap_write_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page, struct iomap * iomap)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582402080,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:699",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582402080,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 633
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
int iomap_write_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582695824,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:730",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582695824,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
size_t iomap_write_end(struct inode * inode, loff_t pos, size_t len, size_t copied, struct page * page, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582766976,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:709",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582766976,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
size_t iomap_write_end(struct inode * inode, loff_t pos, size_t len, size_t copied, struct page * page, struct iomap * iomap, struct iomap * srcmap)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582795984,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:709",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582795984,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
size_t iomap_write_end(struct iomap_iter * iter, loff_t pos, size_t len, size_t copied, struct page * page)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583121520,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:695",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583121520,
      "name": "iomap_write_end",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
size_t iomap_write_end(struct iomap_iter * iter, loff_t pos, size_t len, size_t copied, struct folio * folio)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:698",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583605152,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 734
    },
    {
      "addr": 18446744071594025345,
      "name": "iomap_write_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
size_t iomap_write_end(struct iomap_iter * iter, loff_t pos, size_t len, size_t copied, struct folio * folio)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:712",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584209808,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
    },
    {
      "addr": 18446744071596060867,
      "name": "iomap_write_end.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
size_t iomap_write_end(struct iomap_iter * iter, loff_t pos, size_t len, size_t copied, struct folio * folio)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:734",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584439568,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
    },
    {
      "addr": 18446744071596585024,
      "name": "iomap_write_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
size_t iomap_write_end(struct iomap_iter * iter, loff_t pos, size_t len, size_t copied, struct folio * folio)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:837",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584661968,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
    },
    {
      "addr": 18446744071597490461,
      "name": "iomap_write_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
int iomap_write_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page, struct iomap * iomap)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494002488,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:699",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494002488,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
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
int iomap_write_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page, struct iomap * iomap)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227468836,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:699",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227468836,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
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
int iomap_write_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page, struct iomap * iomap)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287650720,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:699",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287650720,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 980
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
int iomap_write_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page, struct iomap * iomap)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273516584,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:699",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273516584,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int iomap_write_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page, struct iomap * iomap)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582370816,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:699",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582370816,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 633
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
int iomap_write_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page, struct iomap * iomap)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582308512,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:699",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582308512,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 633
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
int iomap_write_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page, struct iomap * iomap)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582361296,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:699",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582361296,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 633
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
int iomap_write_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page, struct iomap * iomap)
```

```json
{
  "name": "iomap_write_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582440992,
      "name": "iomap_write_end",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:699",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440992,
      "name": "iomap_write_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
int iomap_write_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iomap * iomap</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iomap * srcmap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int len</code> ➡️ <code>size_t len</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int copied</code> ➡️ <code>size_t copied</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>size_t</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iomap_iter * iter</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iomap * iomap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iomap * srcmap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
</ul>
</details>
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
