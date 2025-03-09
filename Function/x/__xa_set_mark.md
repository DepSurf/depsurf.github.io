# Function: <code>__xa_set_mark</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589426064,
      "name": "__xa_set_mark",
      "external": true,
      "loc": "lib/xarray.c:1662",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__set_page_dirty",
        "lib/xarray.c:xa_set_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589426064,
      "name": "__xa_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589883936,
      "name": "__xa_set_mark",
      "external": true,
      "loc": "lib/xarray.c:1689",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__set_page_dirty",
        "lib/xarray.c:xa_set_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589883936,
      "name": "__xa_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590109872,
      "name": "__xa_set_mark",
      "external": true,
      "loc": "lib/xarray.c:1700",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__set_page_dirty",
        "lib/xarray.c:xa_set_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590109872,
      "name": "__xa_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585117626,
      "name": "__xa_set_mark",
      "external": true,
      "loc": "lib/xarray.c:1702",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_set_mark"
      ],
      "caller_func": [
        "fs/buffer.c:__set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585114864,
      "name": "__xa_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585268010,
      "name": "__xa_set_mark",
      "external": true,
      "loc": "lib/xarray.c:1892",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_set_mark"
      ],
      "caller_func": [
        "fs/buffer.c:__set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585264368,
      "name": "__xa_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585151386,
      "name": "__xa_set_mark",
      "external": true,
      "loc": "lib/xarray.c:1893",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_set_mark"
      ],
      "caller_func": [
        "fs/buffer.c:__set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585147200,
      "name": "__xa_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585603962,
      "name": "__xa_set_mark",
      "external": true,
      "loc": "lib/xarray.c:1893",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_set_mark"
      ],
      "caller_func": [
        "mm/page-writeback.c:__set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585598896,
      "name": "__xa_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586755728,
      "name": "__xa_set_mark",
      "external": true,
      "loc": "lib/xarray.c:1900",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_mark_dirty",
        "lib/xarray.c:xa_set_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586755728,
      "name": "__xa_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595920752,
      "name": "__xa_set_mark",
      "external": true,
      "loc": "lib/xarray.c:1900",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_mark_dirty",
        "lib/xarray.c:xa_set_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595920752,
      "name": "__xa_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596439072,
      "name": "__xa_set_mark",
      "external": true,
      "loc": "lib/xarray.c:1898",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_mark_dirty",
        "lib/xarray.c:xa_set_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596439072,
      "name": "__xa_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597334432,
      "name": "__xa_set_mark",
      "external": true,
      "loc": "lib/xarray.c:1904",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_mark_dirty",
        "lib/xarray.c:xa_set_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597334432,
      "name": "__xa_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503891296,
      "name": "__xa_set_mark",
      "external": true,
      "loc": "lib/xarray.c:1700",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__set_page_dirty",
        "lib/xarray.c:xa_set_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503891296,
      "name": "__xa_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236519932,
      "name": "__xa_set_mark",
      "external": true,
      "loc": "lib/xarray.c:1700",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__set_page_dirty",
        "lib/xarray.c:xa_set_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236519932,
      "name": "__xa_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297757920,
      "name": "__xa_set_mark",
      "external": true,
      "loc": "lib/xarray.c:1700",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__set_page_dirty",
        "lib/xarray.c:xa_set_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297757920,
      "name": "__xa_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279782664,
      "name": "__xa_set_mark",
      "external": true,
      "loc": "lib/xarray.c:1700",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__set_page_dirty",
        "lib/xarray.c:xa_set_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279782664,
      "name": "__xa_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589712128,
      "name": "__xa_set_mark",
      "external": true,
      "loc": "lib/xarray.c:1700",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__set_page_dirty",
        "lib/xarray.c:xa_set_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589712128,
      "name": "__xa_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589437904,
      "name": "__xa_set_mark",
      "external": true,
      "loc": "lib/xarray.c:1700",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__set_page_dirty",
        "lib/xarray.c:xa_set_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589437904,
      "name": "__xa_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590155504,
      "name": "__xa_set_mark",
      "external": true,
      "loc": "lib/xarray.c:1700",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__set_page_dirty",
        "lib/xarray.c:xa_set_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590155504,
      "name": "__xa_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_set_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590205888,
      "name": "__xa_set_mark",
      "external": true,
      "loc": "lib/xarray.c:1700",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__set_page_dirty",
        "lib/xarray.c:xa_set_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590205888,
      "name": "__xa_set_mark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void __xa_set_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
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
