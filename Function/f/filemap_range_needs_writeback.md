# Function: <code>filemap_range_needs_writeback</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool filemap_range_needs_writeback(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_needs_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581326208,
      "name": "filemap_range_needs_writeback",
      "external": true,
      "loc": "mm/filemap.c:638",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:__iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581326208,
      "name": "filemap_range_needs_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
bool filemap_range_needs_writeback(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_needs_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581572624,
      "name": "filemap_range_needs_writeback",
      "external": true,
      "loc": "mm/filemap.c:656",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:__iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572624,
      "name": "filemap_range_needs_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "filemap_range_needs_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581947801,
      "name": "filemap_range_needs_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:1159",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583618328,
      "name": "filemap_range_needs_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:1159",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:__iomap_dio_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585598883,
      "name": "filemap_range_needs_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:1159",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_read_iter"
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
  "name": "filemap_range_needs_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582381837,
      "name": "filemap_range_needs_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:1133",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584221590,
      "name": "filemap_range_needs_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:1133",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:__iomap_dio_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586366675,
      "name": "filemap_range_needs_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:1133",
      "file": "block/fops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/fops.c:blkdev_read_iter"
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
  "name": "filemap_range_needs_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582589246,
      "name": "filemap_range_needs_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:1136",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:kiocb_write_and_wait"
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
  "name": "filemap_range_needs_writeback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582753230,
      "name": "filemap_range_needs_writeback",
      "external": false,
      "loc": "include/linux/pagemap.h:1223",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:kiocb_write_and_wait"
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
bool filemap_range_needs_writeback(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool filemap_range_needs_writeback(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```
</details>
</li>
</ul>
