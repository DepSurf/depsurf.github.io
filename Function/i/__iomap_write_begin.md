# Function: <code>__iomap_write_begin</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582143481,
      "name": "__iomap_write_begin",
      "external": false,
      "loc": "fs/iomap.c:631",
      "file": "fs/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582302423,
      "name": "__iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:550",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582401447,
      "name": "__iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:550",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __iomap_write_begin(struct inode * inode, loff_t pos, unsigned int len, int flags, struct page * page, struct iomap * srcmap)
```

```json
{
  "name": "__iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582693888,
      "name": "__iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:569",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582693888,
      "name": "__iomap_write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
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
int __iomap_write_begin(struct inode * inode, loff_t pos, unsigned int len, int flags, struct page * page, struct iomap * srcmap)
```

```json
{
  "name": "__iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582764944,
      "name": "__iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:550",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582764944,
      "name": "__iomap_write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
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
int __iomap_write_begin(struct inode * inode, loff_t pos, unsigned int len, int flags, struct page * page, struct iomap * srcmap)
```

```json
{
  "name": "__iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582793920,
      "name": "__iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:550",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582793920,
      "name": "__iomap_write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
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
int __iomap_write_begin(const struct iomap_iter * iter, loff_t pos, unsigned int len, struct page * page)
```

```json
{
  "name": "__iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:546",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583119040,
      "name": "__iomap_write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
    },
    {
      "addr": 18446744071592245586,
      "name": "__iomap_write_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int __iomap_write_begin(const struct iomap_iter * iter, loff_t pos, size_t len, struct folio * folio)
```

```json
{
  "name": "__iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:546",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583608384,
      "name": "__iomap_write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
    },
    {
      "addr": 18446744071594025963,
      "name": "__iomap_write_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int __iomap_write_begin(const struct iomap_iter * iter, loff_t pos, size_t len, struct folio * folio)
```

```json
{
  "name": "__iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:526",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584214544,
      "name": "__iomap_write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
    },
    {
      "addr": 18446744071596061702,
      "name": "__iomap_write_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
int __iomap_write_begin(const struct iomap_iter * iter, loff_t pos, size_t len, struct folio * folio)
```

```json
{
  "name": "__iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:541",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584444256,
      "name": "__iomap_write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
    },
    {
      "addr": 18446744071596585812,
      "name": "__iomap_write_begin.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int __iomap_write_begin(const struct iomap_iter * iter, loff_t pos, size_t len, struct folio * folio)
```

```json
{
  "name": "__iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:633",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584666672,
      "name": "__iomap_write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
    },
    {
      "addr": 18446744071597491287,
      "name": "__iomap_write_begin.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494003892,
      "name": "__iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:550",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227468144,
      "name": "__iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:550",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287654352,
      "name": "__iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:550",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273518464,
      "name": "__iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:550",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582370183,
      "name": "__iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:550",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582307879,
      "name": "__iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:550",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582360663,
      "name": "__iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:550",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__iomap_write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582440359,
      "name": "__iomap_write_begin",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:550",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __iomap_write_begin(struct inode * inode, loff_t pos, unsigned int len, int flags, struct page * page, struct iomap * srcmap)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<code>const struct iomap_iter * iter</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param removed. </b>
<code>int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iomap * srcmap</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, pos, len, flags, page, srcmap</code> ➡️ <code>iter, pos, len, page</code>
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
<li>
<b>Param type changed. </b>
<code>unsigned int len</code> ➡️ <code>size_t len</code>
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
