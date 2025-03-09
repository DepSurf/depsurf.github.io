# Function: <code>set_page_writeback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580754721,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:386",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581231792,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:386",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581235393,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:386",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581261100,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:386",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597278,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:386",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582095942,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:386",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepages_fill"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580876600,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:463",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581389320,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:463",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581401172,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:463",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581426863,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:463",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581787998,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:463",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582313384,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:463",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580944507,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:479",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581467743,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:479",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479508,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:479",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581507977,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:479",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581877566,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:479",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582401720,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:479",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580988628,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:482",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581523394,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:482",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581534724,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:482",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581560541,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:482",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582114334,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:482",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582485704,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:482",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581092244,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:483",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665731,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:483",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677268,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:483",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581704190,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:483",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582263358,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:483",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582636904,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:483",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581233242,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:490",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581829101,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:490",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581840806,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:490",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581871109,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:490",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582451390,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:490",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582830392,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:490",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581316255,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:507",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581916349,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:507",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581928182,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:507",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581956199,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:507",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582550862,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:507",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582933696,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:507",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581427178,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582053458,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582065764,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582088884,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582723132,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583113757,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581491418,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582131122,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582143412,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582166314,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582825628,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583219553,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581696982,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:556",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582369308,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:556",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582390484,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:556",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582402886,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:556",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582693420,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:556",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583137276,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:556",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583546559,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:556",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581743779,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:560",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582427811,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:560",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582443108,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:560",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582456083,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:560",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582761496,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:560",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583217921,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:560",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583656740,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:560",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581771885,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:560",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582450103,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:560",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582470004,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:560",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582485475,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:560",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582791414,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:560",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583245601,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:560",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583677469,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:560",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582054509,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:580",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582772531,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:580",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582799293,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:580",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583120734,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:580",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583587809,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:580",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584036367,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:580",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584893268,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:580",
      "file": "block/bdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bdev.c:bdev_write_page"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool set_page_writeback(struct page * page)
```

```json
{
  "name": "set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581994640,
      "name": "set_page_writeback",
      "external": true,
      "loc": "mm/folio-compat.c:76",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "block/bdev.c:bdev_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581994640,
      "name": "set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
bool set_page_writeback(struct page * page)
```

```json
{
  "name": "set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582431008,
      "name": "set_page_writeback",
      "external": true,
      "loc": "mm/folio-compat.c:48",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage_fs",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "block/bdev.c:bdev_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582431008,
      "name": "set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
bool set_page_writeback(struct page * page)
```

```json
{
  "name": "set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582636320,
      "name": "set_page_writeback",
      "external": true,
      "loc": "mm/folio-compat.c:49",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage_bdev_sync",
        "mm/page_io.c:swap_writepage_fs",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582636320,
      "name": "set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void set_page_writeback(struct page * page)
```

```json
{
  "name": "set_page_writeback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582807424,
      "name": "set_page_writeback",
      "external": true,
      "loc": "mm/folio-compat.c:49",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582807424,
      "name": "set_page_writeback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492910152,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493674908,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493693416,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493720352,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494497316,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494939716,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226702040,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 3227207204,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3227221172,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3227246716,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 3227933912,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3228350048,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286315040,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287276832,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287294400,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287326484,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288263248,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288813128,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272833872,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273300308,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273311636,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273331864,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273896316,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274245278,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581460266,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582099858,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582112148,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135050,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582794364,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583188289,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581402458,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582037298,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582049588,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072490,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582731516,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583125441,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581451466,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582090338,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582102628,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582125530,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582783244,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583172321,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_page_writeback",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581515930,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582163074,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582175492,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582198522,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582869612,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583265959,
      "name": "set_page_writeback",
      "external": false,
      "loc": "include/linux/page-flags.h:540",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool set_page_writeback(struct page * page)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
</ul>
