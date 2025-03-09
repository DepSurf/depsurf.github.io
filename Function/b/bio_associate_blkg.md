# Function: <code>bio_associate_blkg</code>

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
void bio_associate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_associate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583662896,
      "name": "bio_associate_blkg",
      "external": true,
      "loc": "block/bio.c:2076",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
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
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap.c:iomap_dio_bio_actor",
        "fs/iomap.c:iomap_dio_zero",
        "fs/iomap.c:iomap_read_page_sync",
        "fs/iomap.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/dm-linear.c:linear_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583662896,
      "name": "bio_associate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void bio_associate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_associate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583850928,
      "name": "bio_associate_blkg",
      "external": true,
      "loc": "block/bio.c:2110",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-linear.c:linear_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583850928,
      "name": "bio_associate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void bio_associate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_associate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583950256,
      "name": "bio_associate_blkg",
      "external": true,
      "loc": "block/bio.c:2152",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-linear.c:linear_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583950256,
      "name": "bio_associate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void bio_associate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_associate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584344672,
      "name": "bio_associate_blkg",
      "external": true,
      "loc": "block/bio.c:1731",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/mpage.c:mpage_alloc",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_alloc_ioend",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:io_submit_init_bio",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/blk-core.c:blkcg_bio_issue_check",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:__blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-linear.c:linear_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map_range",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584344672,
      "name": "bio_associate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void bio_associate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_associate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584638080,
      "name": "bio_associate_blkg",
      "external": true,
      "loc": "block/blk-cgroup.c:1862",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/mpage.c:mpage_alloc",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_alloc_ioend",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:io_submit_init_bio",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:__blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm.c:__send_empty_flush",
        "drivers/md/dm-linear.c:linear_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map_range",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584638080,
      "name": "bio_associate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void bio_associate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_associate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584665232,
      "name": "bio_associate_blkg",
      "external": true,
      "loc": "block/blk-cgroup.c:1871",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/mpage.c:mpage_alloc",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm.c:__send_empty_flush",
        "drivers/md/dm-linear.c:linear_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584665232,
      "name": "bio_associate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void bio_associate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_associate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585081072,
      "name": "bio_associate_blkg",
      "external": true,
      "loc": "block/blk-cgroup.c:1865",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_alloc",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm.c:__send_empty_flush",
        "drivers/md/dm-linear.c:linear_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585081072,
      "name": "bio_associate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void bio_associate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_associate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585808128,
      "name": "bio_associate_blkg",
      "external": true,
      "loc": "block/blk-cgroup.c:1953",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_init_clone",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_reset",
        "drivers/md/dm.c:alloc_tio",
        "drivers/md/dm-linear.c:linear_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585808128,
      "name": "bio_associate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void bio_associate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_associate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586589792,
      "name": "bio_associate_blkg",
      "external": true,
      "loc": "block/blk-cgroup.c:1959",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_init_clone",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_reset",
        "drivers/md/dm.c:alloc_tio",
        "drivers/md/dm-linear.c:linear_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586589792,
      "name": "bio_associate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void bio_associate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_associate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586847024,
      "name": "bio_associate_blkg",
      "external": true,
      "loc": "block/blk-cgroup.c:2050",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_init_clone",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_reset",
        "drivers/md/dm.c:alloc_tio",
        "drivers/md/dm-linear.c:linear_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586847024,
      "name": "bio_associate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_associate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_associate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587124336,
      "name": "bio_associate_blkg",
      "external": true,
      "loc": "block/blk-cgroup.c:2063",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_init_clone",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_reset",
        "drivers/md/dm.c:alloc_tio",
        "drivers/md/dm-linear.c:linear_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587124336,
      "name": "bio_associate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void bio_associate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_associate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495774200,
      "name": "bio_associate_blkg",
      "external": true,
      "loc": "block/bio.c:2152",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-linear.c:linear_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495774200,
      "name": "bio_associate_blkg",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void bio_associate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_associate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229123980,
      "name": "bio_associate_blkg",
      "external": true,
      "loc": "block/bio.c:2152",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/mpage.c:mpage_alloc",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-linear.c:linear_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229123980,
      "name": "bio_associate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void bio_associate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_associate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289944448,
      "name": "bio_associate_blkg",
      "external": true,
      "loc": "block/bio.c:2152",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/mpage.c:mpage_alloc",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-linear.c:linear_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289944448,
      "name": "bio_associate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void bio_associate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_associate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274916896,
      "name": "bio_associate_blkg",
      "external": true,
      "loc": "block/bio.c:2152",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/mpage.c:mpage_alloc",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-linear.c:linear_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274916896,
      "name": "bio_associate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void bio_associate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_associate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583918992,
      "name": "bio_associate_blkg",
      "external": true,
      "loc": "block/bio.c:2152",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swap_read_pages",
        "kernel/power/swap.c:write_page",
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-linear.c:linear_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583918992,
      "name": "bio_associate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void bio_associate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_associate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583855952,
      "name": "bio_associate_blkg",
      "external": true,
      "loc": "block/bio.c:2152",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-linear.c:linear_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583855952,
      "name": "bio_associate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void bio_associate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_associate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583902752,
      "name": "bio_associate_blkg",
      "external": true,
      "loc": "block/bio.c:2152",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-linear.c:linear_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583902752,
      "name": "bio_associate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void bio_associate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_associate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584004000,
      "name": "bio_associate_blkg",
      "external": true,
      "loc": "block/bio.c:2152",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-linear.c:linear_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-stripe.c:stripe_map",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584004000,
      "name": "bio_associate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void bio_associate_blkg(struct bio * bio)
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
