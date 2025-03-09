# Function: <code>iomap_iop_set_range_uptodate</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void iomap_iop_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```

```json
{
  "name": "iomap_iop_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582690240,
      "name": "iomap_iop_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:139",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582690240,
      "name": "iomap_iop_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
void iomap_iop_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```

```json
{
  "name": "iomap_iop_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582762000,
      "name": "iomap_iop_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:145",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582762000,
      "name": "iomap_iop_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void iomap_iop_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```

```json
{
  "name": "iomap_iop_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582789984,
      "name": "iomap_iop_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:145",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582789984,
      "name": "iomap_iop_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void iomap_iop_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
```

```json
{
  "name": "iomap_iop_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_iop_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:145",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583115984,
      "name": "iomap_iop_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071592245400,
      "name": "iomap_iop_set_range_uptodate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void iomap_iop_set_range_uptodate(struct folio * folio, struct iomap_page * iop, size_t off, size_t len)
```

```json
{
  "name": "iomap_iop_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_iop_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:139",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_read_inline_data",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583600448,
      "name": "iomap_iop_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071594024700,
      "name": "iomap_iop_set_range_uptodate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void iomap_iop_set_range_uptodate(struct folio * folio, struct iomap_page * iop, size_t off, size_t len)
```

```json
{
  "name": "iomap_iop_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_iop_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:147",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_read_inline_data",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584205744,
      "name": "iomap_iop_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071596060219,
      "name": "iomap_iop_set_range_uptodate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void iomap_iop_set_range_uptodate(struct folio * folio, struct iomap_page * iop, size_t off, size_t len)
```

```json
{
  "name": "iomap_iop_set_range_uptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_iop_set_range_uptodate",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:147",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_read_inline_data",
        "fs/iomap/buffered-io.c:iomap_read_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584435600,
      "name": "iomap_iop_set_range_uptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    },
    {
      "addr": 18446744071596584354,
      "name": "iomap_iop_set_range_uptodate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void iomap_iop_set_range_uptodate(struct page * page, unsigned int off, unsigned int len)
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
<b>Param added. </b>
<code>struct iomap_page * iop</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
<li>
<b>Param reordered. </b>
<code>page, off, len</code> ➡️ <code>folio, iop, off, len</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int off</code> ➡️ <code>size_t off</code>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void iomap_iop_set_range_uptodate(struct folio * folio, struct iomap_page * iop, size_t off, size_t len)
```
</details>
</li>
</ul>
