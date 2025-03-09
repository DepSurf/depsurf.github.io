# Function: <code>__xa_clear_mark</code>

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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589429312,
      "name": "__xa_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:1680",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "lib/xarray.c:xa_clear_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589429312,
      "name": "__xa_clear_mark",
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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589886992,
      "name": "__xa_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:1707",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "lib/xarray.c:xa_clear_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589886992,
      "name": "__xa_clear_mark",
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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590112944,
      "name": "__xa_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:1718",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "lib/xarray.c:xa_clear_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590112944,
      "name": "__xa_clear_mark",
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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585117770,
      "name": "__xa_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:1720",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_clear_mark"
      ],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585116432,
      "name": "__xa_clear_mark",
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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585268154,
      "name": "__xa_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:1910",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_clear_mark"
      ],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585266448,
      "name": "__xa_clear_mark",
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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585151530,
      "name": "__xa_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:1911",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_clear_mark"
      ],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585149584,
      "name": "__xa_clear_mark",
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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585603802,
      "name": "__xa_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:1911",
      "file": "lib/xarray.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xa_clear_mark"
      ],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585601568,
      "name": "__xa_clear_mark",
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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586756208,
      "name": "__xa_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:1918",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_end_writeback",
        "lib/xarray.c:xa_clear_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586756208,
      "name": "__xa_clear_mark",
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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595922864,
      "name": "__xa_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:1918",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_end_writeback",
        "lib/xarray.c:xa_clear_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595922864,
      "name": "__xa_clear_mark",
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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596441616,
      "name": "__xa_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:1916",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_end_writeback",
        "lib/xarray.c:xa_clear_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596441616,
      "name": "__xa_clear_mark",
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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597336976,
      "name": "__xa_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:1922",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_end_writeback",
        "lib/xarray.c:xa_clear_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597336976,
      "name": "__xa_clear_mark",
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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503894200,
      "name": "__xa_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:1718",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "lib/xarray.c:xa_clear_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503894200,
      "name": "__xa_clear_mark",
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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236523576,
      "name": "__xa_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:1718",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "lib/xarray.c:xa_clear_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236523576,
      "name": "__xa_clear_mark",
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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297762256,
      "name": "__xa_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:1718",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "lib/xarray.c:xa_clear_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297762256,
      "name": "__xa_clear_mark",
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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279785820,
      "name": "__xa_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:1718",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "lib/xarray.c:xa_clear_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279785820,
      "name": "__xa_clear_mark",
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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589715200,
      "name": "__xa_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:1718",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "lib/xarray.c:xa_clear_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589715200,
      "name": "__xa_clear_mark",
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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589440976,
      "name": "__xa_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:1718",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "lib/xarray.c:xa_clear_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589440976,
      "name": "__xa_clear_mark",
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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590158576,
      "name": "__xa_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:1718",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "lib/xarray.c:xa_clear_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590158576,
      "name": "__xa_clear_mark",
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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
```

```json
{
  "name": "__xa_clear_mark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590209152,
      "name": "__xa_clear_mark",
      "external": true,
      "loc": "lib/xarray.c:1718",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "lib/xarray.c:xa_clear_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590209152,
      "name": "__xa_clear_mark",
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
void __xa_clear_mark(struct xarray * xa, long unsigned int index, xa_mark_t mark)
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
