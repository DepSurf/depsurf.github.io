# Function: <code>iomap_page_create</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iomap_page * iomap_page_create(struct inode * inode, struct page * page)
```

```json
{
  "name": "iomap_page_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582139808,
      "name": "iomap_page_create",
      "external": false,
      "loc": "fs/iomap.c:108",
      "file": "fs/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582139808,
      "name": "iomap_page_create",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iomap_page * iomap_page_create(struct inode * inode, struct page * page)
```

```json
{
  "name": "iomap_page_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582300080,
      "name": "iomap_page_create",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:23",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582300080,
      "name": "iomap_page_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
struct iomap_page * iomap_page_create(struct inode * inode, struct page * page)
```

```json
{
  "name": "iomap_page_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582399104,
      "name": "iomap_page_create",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:23",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582399104,
      "name": "iomap_page_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_page_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582693947,
      "name": "iomap_page_create",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:45",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": [
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582688912,
      "name": "iomap_page_create.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
struct iomap_page * iomap_page_create(struct inode * inode, struct page * page)
```

```json
{
  "name": "iomap_page_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582763952,
      "name": "iomap_page_create",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:52",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582763952,
      "name": "iomap_page_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
struct iomap_page * iomap_page_create(struct inode * inode, struct page * page)
```

```json
{
  "name": "iomap_page_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582792896,
      "name": "iomap_page_create",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:52",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792896,
      "name": "iomap_page_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
struct iomap_page * iomap_page_create(struct inode * inode, struct page * page)
```

```json
{
  "name": "iomap_page_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_page_create",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:52",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_read_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583117136,
      "name": "iomap_page_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071592245516,
      "name": "iomap_page_create.cold",
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
struct iomap_page * iomap_page_create(struct inode * inode, struct folio * folio)
```

```json
{
  "name": "iomap_page_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_page_create",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:47",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_read_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583600784,
      "name": "iomap_page_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071594024829,
      "name": "iomap_page_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
struct iomap_page * iomap_page_create(struct inode * inode, struct folio * folio, unsigned int flags)
```

```json
{
  "name": "iomap_page_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_page_create",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:47",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_read_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584206048,
      "name": "iomap_page_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446744071596060356,
      "name": "iomap_page_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
struct iomap_page * iomap_page_create(struct inode * inode, struct folio * folio, unsigned int flags)
```

```json
{
  "name": "iomap_page_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_page_create",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:47",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_read_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584435888,
      "name": "iomap_page_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071596584478,
      "name": "iomap_page_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct iomap_page * iomap_page_create(struct inode * inode, struct page * page)
```

```json
{
  "name": "iomap_page_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493999400,
      "name": "iomap_page_create",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:23",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493999400,
      "name": "iomap_page_create",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct iomap_page * iomap_page_create(struct inode * inode, struct page * page)
```

```json
{
  "name": "iomap_page_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227463456,
      "name": "iomap_page_create",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:23",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227463456,
      "name": "iomap_page_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct iomap_page * iomap_page_create(struct inode * inode, struct page * page)
```

```json
{
  "name": "iomap_page_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287648288,
      "name": "iomap_page_create",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:23",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287648288,
      "name": "iomap_page_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct iomap_page * iomap_page_create(struct inode * inode, struct page * page)
```

```json
{
  "name": "iomap_page_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273514482,
      "name": "iomap_page_create",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:23",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273514482,
      "name": "iomap_page_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
struct iomap_page * iomap_page_create(struct inode * inode, struct page * page)
```

```json
{
  "name": "iomap_page_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582367840,
      "name": "iomap_page_create",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:23",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582367840,
      "name": "iomap_page_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
struct iomap_page * iomap_page_create(struct inode * inode, struct page * page)
```

```json
{
  "name": "iomap_page_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582305536,
      "name": "iomap_page_create",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:23",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582305536,
      "name": "iomap_page_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
struct iomap_page * iomap_page_create(struct inode * inode, struct page * page)
```

```json
{
  "name": "iomap_page_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582358320,
      "name": "iomap_page_create",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:23",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582358320,
      "name": "iomap_page_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
struct iomap_page * iomap_page_create(struct inode * inode, struct page * page)
```

```json
{
  "name": "iomap_page_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582437952,
      "name": "iomap_page_create",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:23",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582437952,
      "name": "iomap_page_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct iomap_page * iomap_page_create(struct inode * inode, struct page * page)
```
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct iomap_page * iomap_page_create(struct inode * inode, struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct iomap_page * iomap_page_create(struct inode * inode, struct page * page)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct iomap_page * iomap_page_create(struct inode * inode, struct folio * folio, unsigned int flags)
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
