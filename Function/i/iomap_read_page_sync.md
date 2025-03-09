# Function: <code>iomap_read_page_sync</code>

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
int iomap_read_page_sync(struct inode * inode, loff_t block_start, struct page * page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap * iomap)
```

```json
{
  "name": "iomap_read_page_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582142816,
      "name": "iomap_read_page_sync",
      "external": false,
      "loc": "fs/iomap.c:609",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582142816,
      "name": "iomap_read_page_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int iomap_read_page_sync(struct inode * inode, loff_t block_start, struct page * page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap * iomap)
```

```json
{
  "name": "iomap_read_page_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582301712,
      "name": "iomap_read_page_sync",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:528",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301712,
      "name": "iomap_read_page_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int iomap_read_page_sync(struct inode * inode, loff_t block_start, struct page * page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap * iomap)
```

```json
{
  "name": "iomap_read_page_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582400736,
      "name": "iomap_read_page_sync",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:528",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582400736,
      "name": "iomap_read_page_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int iomap_read_page_sync(loff_t block_start, struct page * page, unsigned int poff, unsigned int plen, struct iomap * iomap)
```

```json
{
  "name": "iomap_read_page_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582687024,
      "name": "iomap_read_page_sync",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:554",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:__iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582687024,
      "name": "iomap_read_page_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int iomap_read_page_sync(loff_t block_start, struct page * page, unsigned int poff, unsigned int plen, struct iomap * iomap)
```

```json
{
  "name": "iomap_read_page_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582758272,
      "name": "iomap_read_page_sync",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:535",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:__iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582758272,
      "name": "iomap_read_page_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
int iomap_read_page_sync(loff_t block_start, struct page * page, unsigned int poff, unsigned int plen, struct iomap * iomap)
```

```json
{
  "name": "iomap_read_page_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582787232,
      "name": "iomap_read_page_sync",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:535",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:__iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582787232,
      "name": "iomap_read_page_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int iomap_read_page_sync(loff_t block_start, struct page * page, unsigned int poff, unsigned int plen, const struct iomap * iomap)
```

```json
{
  "name": "iomap_read_page_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583113152,
      "name": "iomap_read_page_sync",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:532",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:__iomap_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583113152,
      "name": "iomap_read_page_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int iomap_read_page_sync(struct inode * inode, loff_t block_start, struct page * page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap * iomap)
```

```json
{
  "name": "iomap_read_page_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494003168,
      "name": "iomap_read_page_sync",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:528",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494003168,
      "name": "iomap_read_page_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
int iomap_read_page_sync(struct inode * inode, loff_t block_start, struct page * page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap * iomap)
```

```json
{
  "name": "iomap_read_page_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227467276,
      "name": "iomap_read_page_sync",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:528",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227467276,
      "name": "iomap_read_page_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int iomap_read_page_sync(struct inode * inode, loff_t block_start, struct page * page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap * iomap)
```

```json
{
  "name": "iomap_read_page_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287653424,
      "name": "iomap_read_page_sync",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:528",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287653424,
      "name": "iomap_read_page_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int iomap_read_page_sync(struct inode * inode, loff_t block_start, struct page * page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap * iomap)
```

```json
{
  "name": "iomap_read_page_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273517826,
      "name": "iomap_read_page_sync",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:528",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273517826,
      "name": "iomap_read_page_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
int iomap_read_page_sync(struct inode * inode, loff_t block_start, struct page * page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap * iomap)
```

```json
{
  "name": "iomap_read_page_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582369472,
      "name": "iomap_read_page_sync",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:528",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582369472,
      "name": "iomap_read_page_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int iomap_read_page_sync(struct inode * inode, loff_t block_start, struct page * page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap * iomap)
```

```json
{
  "name": "iomap_read_page_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582307168,
      "name": "iomap_read_page_sync",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:528",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582307168,
      "name": "iomap_read_page_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int iomap_read_page_sync(struct inode * inode, loff_t block_start, struct page * page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap * iomap)
```

```json
{
  "name": "iomap_read_page_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582359952,
      "name": "iomap_read_page_sync",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:528",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582359952,
      "name": "iomap_read_page_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int iomap_read_page_sync(struct inode * inode, loff_t block_start, struct page * page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap * iomap)
```

```json
{
  "name": "iomap_read_page_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582439616,
      "name": "iomap_read_page_sync",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:528",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582439616,
      "name": "iomap_read_page_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int iomap_read_page_sync(struct inode * inode, loff_t block_start, struct page * page, unsigned int poff, unsigned int plen, unsigned int from, unsigned int to, struct iomap * iomap)
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int from</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int to</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, block_start, page, poff, plen, from, to, iomap</code> ➡️ <code>block_start, page, poff, plen, iomap</code>
</li>
</ul>
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
<b>Param type changed. </b>
<code>struct iomap * iomap</code> ➡️ <code>const struct iomap * iomap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int iomap_read_page_sync(loff_t block_start, struct page * page, unsigned int poff, unsigned int plen, const struct iomap * iomap)
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
