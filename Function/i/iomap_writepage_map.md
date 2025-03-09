# Function: <code>iomap_writepage_map</code>

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
int iomap_writepage_map(struct iomap_writepage_ctx * wpc, struct writeback_control * wbc, struct inode * inode, struct page * page, u64 end_offset)
```

```json
{
  "name": "iomap_writepage_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582692944,
      "name": "iomap_writepage_map",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1367",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_do_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582692944,
      "name": "iomap_writepage_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 930
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
int iomap_writepage_map(struct iomap_writepage_ctx * wpc, struct writeback_control * wbc, struct inode * inode, struct page * page, u64 end_offset)
```

```json
{
  "name": "iomap_writepage_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582760992,
      "name": "iomap_writepage_map",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1337",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_do_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582760992,
      "name": "iomap_writepage_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
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
int iomap_writepage_map(struct iomap_writepage_ctx * wpc, struct writeback_control * wbc, struct inode * inode, struct page * page, u64 end_offset)
```

```json
{
  "name": "iomap_writepage_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582790912,
      "name": "iomap_writepage_map",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1333",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_do_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582790912,
      "name": "iomap_writepage_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1006
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
int iomap_writepage_map(struct iomap_writepage_ctx * wpc, struct writeback_control * wbc, struct inode * inode, struct page * page, u64 end_offset)
```

```json
{
  "name": "iomap_writepage_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_writepage_map",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1295",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_do_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583120304,
      "name": "iomap_writepage_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 869
    },
    {
      "addr": 18446744071592245620,
      "name": "iomap_writepage_map.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int iomap_writepage_map(struct iomap_writepage_ctx * wpc, struct writeback_control * wbc, struct inode * inode, struct folio * folio, u64 end_pos)
```

```json
{
  "name": "iomap_writepage_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_writepage_map",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1328",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_do_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583602528,
      "name": "iomap_writepage_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1020
    },
    {
      "addr": 18446744071594025052,
      "name": "iomap_writepage_map.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int iomap_writepage_map(struct iomap_writepage_ctx * wpc, struct writeback_control * wbc, struct inode * inode, struct folio * folio, u64 end_pos)
```

```json
{
  "name": "iomap_writepage_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_writepage_map",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1589",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_do_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584208448,
      "name": "iomap_writepage_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1031
    },
    {
      "addr": 18446744071596060687,
      "name": "iomap_writepage_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int iomap_writepage_map(struct iomap_writepage_ctx * wpc, struct writeback_control * wbc, struct inode * inode, struct folio * folio, u64 end_pos)
```

```json
{
  "name": "iomap_writepage_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_writepage_map",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1609",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_do_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584438496,
      "name": "iomap_writepage_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1042
    },
    {
      "addr": 18446744071596584825,
      "name": "iomap_writepage_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
int iomap_writepage_map(struct iomap_writepage_ctx * wpc, struct writeback_control * wbc, struct inode * inode, struct folio * folio, u64 end_pos)
```

```json
{
  "name": "iomap_writepage_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_writepage_map",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1777",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_do_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584660320,
      "name": "iomap_writepage_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1253
    },
    {
      "addr": 18446744071597490048,
      "name": "iomap_writepage_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
int iomap_writepage_map(struct iomap_writepage_ctx * wpc, struct writeback_control * wbc, struct inode * inode, struct page * page, u64 end_offset)
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
<code>u64 end_pos</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 end_offset</code>
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
