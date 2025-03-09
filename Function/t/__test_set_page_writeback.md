# Function: <code>__test_set_page_writeback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580527648,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2751",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580527648,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 457
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580605488,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2798",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580605488,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580672624,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2765",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580672624,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580710272,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2775",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580710272,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 772
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580795808,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2758",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580795808,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935760,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2758",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935760,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 985
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581003392,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2752",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003392,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 910
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
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581067792,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2760",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581067792,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 784
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
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581123760,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2764",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123760,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 784
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
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581310400,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2774",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581310400,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 768
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
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581357424,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2766",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581357424,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
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
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581376624,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2763",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581376624,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
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
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581625600,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2813",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "block/bdev.c:bdev_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581625600,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492498576,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2764",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492498576,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 896
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
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226365452,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2764",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226365452,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285782096,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2764",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285782096,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1084
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
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272556150,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2764",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272556150,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581092608,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2764",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581092608,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 784
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
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581039792,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2764",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581039792,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 762
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
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581083808,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2764",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581083808,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 784
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
int __test_set_page_writeback(struct page * page, bool keep_write)
```

```json
{
  "name": "__test_set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145728,
      "name": "__test_set_page_writeback",
      "external": true,
      "loc": "mm/page-writeback.c:2764",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/block_dev.c:bdev_write_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145728,
      "name": "__test_set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 784
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int __test_set_page_writeback(struct page * page, bool keep_write)
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
