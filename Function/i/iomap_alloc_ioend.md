# Function: <code>iomap_alloc_ioend</code>

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
struct iomap_ioend * iomap_alloc_ioend(struct inode * inode, struct iomap_writepage_ctx * wpc, loff_t offset, sector_t sector, struct writeback_control * wbc)
```

```json
{
  "name": "iomap_alloc_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582687488,
      "name": "iomap_alloc_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1248",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582687488,
      "name": "iomap_alloc_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
struct iomap_ioend * iomap_alloc_ioend(struct inode * inode, struct iomap_writepage_ctx * wpc, loff_t offset, sector_t sector, struct writeback_control * wbc)
```

```json
{
  "name": "iomap_alloc_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582758736,
      "name": "iomap_alloc_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1218",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582758736,
      "name": "iomap_alloc_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_alloc_ioend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582787896,
      "name": "iomap_alloc_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1215",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend"
      ],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_alloc_ioend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583115421,
      "name": "iomap_alloc_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1184",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend"
      ],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_alloc_ioend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583601969,
      "name": "iomap_alloc_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1211",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend"
      ],
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_alloc_ioend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584206572,
      "name": "iomap_alloc_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1472",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend"
      ],
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_alloc_ioend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584436391,
      "name": "iomap_alloc_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1492",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend"
      ],
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_alloc_ioend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584658297,
      "name": "iomap_alloc_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1660",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
struct iomap_ioend * iomap_alloc_ioend(struct inode * inode, struct iomap_writepage_ctx * wpc, loff_t offset, sector_t sector, struct writeback_control * wbc)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct iomap_ioend * iomap_alloc_ioend(struct inode * inode, struct iomap_writepage_ctx * wpc, loff_t offset, sector_t sector, struct writeback_control * wbc)
```
</details>
</li>
</ul>
