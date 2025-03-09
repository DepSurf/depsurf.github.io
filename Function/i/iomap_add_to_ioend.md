# Function: <code>iomap_add_to_ioend</code>

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
void iomap_add_to_ioend(struct inode * inode, loff_t offset, struct page * page, struct iomap_page * iop, struct iomap_writepage_ctx * wpc, struct writeback_control * wbc, struct list_head * iolist)
```

```json
{
  "name": "iomap_add_to_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582687792,
      "name": "iomap_add_to_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1318",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582687792,
      "name": "iomap_add_to_ioend",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void iomap_add_to_ioend(struct inode * inode, loff_t offset, struct page * page, struct iomap_page * iop, struct iomap_writepage_ctx * wpc, struct writeback_control * wbc, struct list_head * iolist)
```

```json
{
  "name": "iomap_add_to_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582759040,
      "name": "iomap_add_to_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1288",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582759040,
      "name": "iomap_add_to_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
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
void iomap_add_to_ioend(struct inode * inode, loff_t offset, struct page * page, struct iomap_page * iop, struct iomap_writepage_ctx * wpc, struct writeback_control * wbc, struct list_head * iolist)
```

```json
{
  "name": "iomap_add_to_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582787696,
      "name": "iomap_add_to_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1284",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582787696,
      "name": "iomap_add_to_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 780
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
void iomap_add_to_ioend(struct inode * inode, loff_t offset, struct page * page, struct iomap_page * iop, struct iomap_writepage_ctx * wpc, struct writeback_control * wbc, struct list_head * iolist)
```

```json
{
  "name": "iomap_add_to_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_add_to_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1253",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583115232,
      "name": "iomap_add_to_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
    },
    {
      "addr": 18446744071592245343,
      "name": "iomap_add_to_ioend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void iomap_add_to_ioend(struct inode * inode, loff_t pos, struct folio * folio, struct iomap_page * iop, struct iomap_writepage_ctx * wpc, struct writeback_control * wbc, struct list_head * iolist)
```

```json
{
  "name": "iomap_add_to_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_add_to_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1286",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583601728,
      "name": "iomap_add_to_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
    },
    {
      "addr": 18446744071594024929,
      "name": "iomap_add_to_ioend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void iomap_add_to_ioend(struct inode * inode, loff_t pos, struct folio * folio, struct iomap_page * iop, struct iomap_writepage_ctx * wpc, struct writeback_control * wbc, struct list_head * iolist)
```

```json
{
  "name": "iomap_add_to_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_add_to_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1547",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584206336,
      "name": "iomap_add_to_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    },
    {
      "addr": 18446744071596060420,
      "name": "iomap_add_to_ioend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void iomap_add_to_ioend(struct inode * inode, loff_t pos, struct folio * folio, struct iomap_page * iop, struct iomap_writepage_ctx * wpc, struct writeback_control * wbc, struct list_head * iolist)
```

```json
{
  "name": "iomap_add_to_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_add_to_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1567",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584436160,
      "name": "iomap_add_to_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
    },
    {
      "addr": 18446744071596584529,
      "name": "iomap_add_to_ioend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void iomap_add_to_ioend(struct inode * inode, loff_t pos, struct folio * folio, struct iomap_folio_state * ifs, struct iomap_writepage_ctx * wpc, struct writeback_control * wbc, struct list_head * iolist)
```

```json
{
  "name": "iomap_add_to_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_add_to_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1735",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584658064,
      "name": "iomap_add_to_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 697
    },
    {
      "addr": 18446744071597489723,
      "name": "iomap_add_to_ioend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void iomap_add_to_ioend(struct inode * inode, loff_t offset, struct page * page, struct iomap_page * iop, struct iomap_writepage_ctx * wpc, struct writeback_control * wbc, struct list_head * iolist)
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
<code>loff_t pos</code>
</li>
<li>
<b>Param added. </b>
<code>struct folio * folio</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t offset</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iomap_folio_state * ifs</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iomap_page * iop</code>
</li>
</ul>
</details>
</li>
</ul>
