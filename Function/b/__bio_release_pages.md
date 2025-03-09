# Function: <code>__bio_release_pages</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __bio_release_pages(struct bio * bio, bool mark_dirty)
```

```json
{
  "name": "__bio_release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585603968,
      "name": "__bio_release_pages",
      "external": true,
      "loc": "block/bio.c:1120",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585603968,
      "name": "__bio_release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
void __bio_release_pages(struct bio * bio, bool mark_dirty)
```

```json
{
  "name": "__bio_release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586372288,
      "name": "__bio_release_pages",
      "external": true,
      "loc": "block/bio.c:1172",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586372288,
      "name": "__bio_release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
void __bio_release_pages(struct bio * bio, bool mark_dirty)
```

```json
{
  "name": "__bio_release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586617392,
      "name": "__bio_release_pages",
      "external": true,
      "loc": "block/bio.c:1148",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586617392,
      "name": "__bio_release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void __bio_release_pages(struct bio * bio, bool mark_dirty)
```

```json
{
  "name": "__bio_release_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bio_release_pages",
      "external": true,
      "loc": "block/bio.c:1149",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:dio_bio_complete",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/bio.c:bio_dirty_fn",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597534443,
      "name": "__bio_release_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586887616,
      "name": "__bio_release_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void __bio_release_pages(struct bio * bio, bool mark_dirty)
```
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
