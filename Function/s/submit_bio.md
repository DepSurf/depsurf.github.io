# Function: <code>submit_bio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
blk_qc_t submit_bio(int rw, struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582752064,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:2095",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_readpage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:mpage_readpage",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "drivers/block/xen-blkfront.c:blkif_recover",
        "drivers/block/xen-blkfront.c:blkif_recover",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_super_write",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582752064,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583030048,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:2067",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_bio_submit",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:next_bio",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/md.c:md_super_write",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583030048,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583134816,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:2050",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap.c:iomap_dio_actor",
        "fs/iomap.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:next_bio",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583134816,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583191744,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:2237",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap.c:iomap_dio_actor",
        "fs/iomap.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:next_bio",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583191744,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583368080,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:2394",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap.c:iomap_dio_actor",
        "fs/iomap.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:next_bio",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583368080,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583577728,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:2537",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap.c:iomap_dio_actor",
        "fs/iomap.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:next_bio",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583577728,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583690304,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:1167",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap.c:iomap_dio_bio_actor",
        "fs/iomap.c:iomap_dio_zero",
        "fs/iomap.c:iomap_readpages",
        "fs/iomap.c:iomap_readpage",
        "fs/iomap.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:blk_next_bio",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583690304,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583878912,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:1129",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:blk_next_bio",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583878912,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583981872,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:1144",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:blk_next_bio",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583981872,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584371664,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:1224",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_submit_ioend",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_submit_bio",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:__blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584371664,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584487984,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:1079",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:dio_zero_block",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_submit_ioend",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_submit_bio",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:__blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584487984,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584522640,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:1065",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:dio_zero_block",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_submit_ioend",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_submit_bio",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584522640,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584930080,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:1051",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:dio_zero_block",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_submit_ioend",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/direct-io.c:iomap_dio_submit_bio",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584930080,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585634512,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:873",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_read_folio",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_submit_ioend",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/direct-io.c:iomap_dio_submit_bio",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/fops.c:__blkdev_direct_IO_async",
        "block/fops.c:__blkdev_direct_IO_async",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:__blkdev_direct_IO",
        "block/bio.c:submit_bio_wait",
        "block/bio.c:blk_next_bio",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585634512,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586405776,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:827",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_read_folio",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_submit_ioend",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/direct-io.c:iomap_dio_submit_bio",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/fops.c:__blkdev_direct_IO_async",
        "block/fops.c:__blkdev_direct_IO_async",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:__blkdev_direct_IO",
        "block/bio.c:submit_bio_wait",
        "block/bio.c:blk_next_bio",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/md.c:md_super_write",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586405776,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586653056,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:824",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_read_folio",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_submit_ioend",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/direct-io.c:iomap_dio_submit_bio",
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/squashfs/block.c:squashfs_bio_read_cached",
        "block/fops.c:__blkdev_direct_IO_async",
        "block/fops.c:__blkdev_direct_IO_async",
        "block/bio.c:submit_bio_wait",
        "block/bio.c:blk_next_bio",
        "block/blk-cgroup.c:blkcg_punt_bio_submit",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/md.c:md_super_write",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586653056,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586924176,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:858",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_read_folio",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_read_folio",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_submit_ioend",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/direct-io.c:iomap_dio_submit_bio",
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/squashfs/block.c:squashfs_bio_read_cached",
        "block/fops.c:__blkdev_direct_IO_async",
        "block/fops.c:__blkdev_direct_IO_async",
        "block/bio.c:submit_bio_wait",
        "block/bio.c:blk_next_bio",
        "block/blk-cgroup.c:blkcg_punt_bio_submit",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/md.c:md_super_write",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586924176,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495806176,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:1144",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:blk_next_bio",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495806176,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229157852,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:1144",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_submit_bio",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:blk_next_bio",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229157852,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289991328,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:1144",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:blk_next_bio",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289991328,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 724
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
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274944446,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:1144",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:blk_next_bio",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274944446,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583950608,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:1144",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swap_read_pages",
        "kernel/power/swap.c:write_page",
        "kernel/power/swap.c:write_page",
        "kernel/power/swap.c:hib_wait_io",
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:blk_next_bio",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583950608,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583887536,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:1144",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:blk_next_bio",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583887536,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583934368,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:1144",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:blk_next_bio",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583934368,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
blk_qc_t submit_bio(struct bio * bio)
```

```json
{
  "name": "submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584036000,
      "name": "submit_bio",
      "external": true,
      "loc": "block/blk-core.c:1144",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:submit_bio_wait",
        "block/blk-lib.c:blk_next_bio",
        "block/blk-cgroup.c:blkg_async_bio_workfn",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584036000,
      "name": "submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
<li>
<b>Param reordered. </b>
<code>rw, bio</code> ➡️ <code>bio</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>blk_qc_t</code> ➡️ <code>void</code>
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
