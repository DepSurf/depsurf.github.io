# Function: <code>fuse_range_is_writeback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582078400,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:338",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582078400,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582293520,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:338",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582293520,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582381904,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:339",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381904,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582467200,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:334",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582467200,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582615472,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:334",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582615472,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582813296,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:334",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582813296,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582916576,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:338",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582916576,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583094928,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:362",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583094928,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583197840,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:390",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583197840,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583526304,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:397",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepage_need_send",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583526304,
      "name": "fuse_range_is_writeback",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583636400,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:420",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepage_need_send",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583636400,
      "name": "fuse_range_is_writeback",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583657216,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:424",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583657216,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584015840,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:428",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584015840,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584597920,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:434",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_launder_folio",
        "fs/fuse/file.c:fuse_launder_folio",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584597920,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585276416,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:434",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_launder_folio",
        "fs/fuse/file.c:fuse_launder_folio",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585276416,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585506896,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:435",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_launder_folio",
        "fs/fuse/file.c:fuse_launder_folio",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585506896,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585743648,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:436",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_launder_folio",
        "fs/fuse/file.c:fuse_launder_folio",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write_pages",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585743648,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494919672,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:390",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494919672,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228327352,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:390",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228327352,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288781248,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:390",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288781248,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274226550,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:390",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274226550,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583166576,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:390",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583166576,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583103728,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:390",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583103728,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583150608,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:390",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583150608,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
bool fuse_range_is_writeback(struct inode * inode, long unsigned int idx_from, long unsigned int idx_to)
```

```json
{
  "name": "fuse_range_is_writeback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583242400,
      "name": "fuse_range_is_writeback",
      "external": false,
      "loc": "fs/fuse/file.c:390",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583242400,
      "name": "fuse_range_is_writeback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
