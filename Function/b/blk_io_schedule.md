# Function: <code>blk_io_schedule</code>

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
void blk_io_schedule()
```

```json
{
  "name": "blk_io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584361904,
      "name": "blk_io_schedule",
      "external": true,
      "loc": "block/blk-core.c:1883",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_await_one",
        "fs/iomap/direct-io.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584361904,
      "name": "blk_io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void blk_io_schedule()
```

```json
{
  "name": "blk_io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584478912,
      "name": "blk_io_schedule",
      "external": true,
      "loc": "block/blk-core.c:1778",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_await_one",
        "fs/iomap/direct-io.c:__iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584478912,
      "name": "blk_io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void blk_io_schedule()
```

```json
{
  "name": "blk_io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584513632,
      "name": "blk_io_schedule",
      "external": true,
      "loc": "block/blk-core.c:1770",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:__iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584513632,
      "name": "blk_io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void blk_io_schedule()
```

```json
{
  "name": "blk_io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584924848,
      "name": "blk_io_schedule",
      "external": true,
      "loc": "block/blk-core.c:1756",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:__blkdev_direct_IO_simple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584924848,
      "name": "blk_io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void blk_io_schedule()
```

```json
{
  "name": "blk_io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585628800,
      "name": "blk_io_schedule",
      "external": true,
      "loc": "block/blk-core.c:1236",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "block/fops.c:__blkdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585628800,
      "name": "blk_io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void blk_io_schedule()
```

```json
{
  "name": "blk_io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586396512,
      "name": "blk_io_schedule",
      "external": true,
      "loc": "block/blk-core.c:1174",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "block/fops.c:__blkdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586396512,
      "name": "blk_io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void blk_io_schedule()
```

```json
{
  "name": "blk_io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586643328,
      "name": "blk_io_schedule",
      "external": true,
      "loc": "block/blk-core.c:1171",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/iomap/direct-io.c:__iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586643328,
      "name": "blk_io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void blk_io_schedule()
```

```json
{
  "name": "blk_io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586914288,
      "name": "blk_io_schedule",
      "external": true,
      "loc": "block/blk-core.c:1206",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/iomap/direct-io.c:__iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586914288,
      "name": "blk_io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void blk_io_schedule()
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
