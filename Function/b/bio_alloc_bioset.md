# Function: <code>bio_alloc_bioset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bio * bio_alloc_bioset(gfp_t gfp_mask, int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582717776,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:423",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
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
        "fs/mpage.c:mpage_alloc",
        "fs/mpage.c:mpage_alloc",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/crypto.c:ext4_encrypted_zeroout",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_clone_bioset",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_copy_kern",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "drivers/md/dm.c:__clone_and_map_simple_bio",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582717776,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582994736,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:422",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/buffer.c:submit_bh_wbc",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_alloc",
        "fs/mpage.c:mpage_alloc",
        "fs/crypto/crypto.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_clone_bioset",
        "block/bio.c:bio_clone_fast",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:next_bio",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__clone_and_map_simple_bio",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582994736,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583099664,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:426",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
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
        "fs/mpage.c:mpage_alloc",
        "fs/mpage.c:mpage_alloc",
        "fs/crypto/crypto.c:fscrypt_zeroout_range",
        "fs/iomap.c:iomap_dio_actor",
        "fs/iomap.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_clone_bioset",
        "block/bio.c:bio_clone_fast",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:next_bio",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_report_zones",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__clone_and_map_simple_bio",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583099664,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583155920,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:436",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_alloc",
        "fs/mpage.c:mpage_alloc",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap.c:iomap_dio_actor",
        "fs/iomap.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_clone_bioset",
        "block/bio.c:bio_clone_fast",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:next_bio",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_report_zones",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__clone_and_map_simple_bio",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583155920,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583330960,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:436",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap.c:iomap_dio_actor",
        "fs/iomap.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_clone_bioset",
        "block/bio.c:bio_clone_fast",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:next_bio",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_report_zones",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__clone_and_map_simple_bio",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583330960,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583540192,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:436",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap.c:iomap_dio_actor",
        "fs/iomap.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_clone_bioset",
        "block/bio.c:bio_clone_fast",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:next_bio",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_report_zones",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583540192,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583664288,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:438",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
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
        "fs/iomap.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_clone_fast",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blk_next_bio",
        "block/bounce.c:blk_queue_bounce",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583664288,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583852672,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:426",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_clone_fast",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blk_next_bio",
        "block/bounce.c:__blk_queue_bounce",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583852672,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 495
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583954560,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:429",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_clone_fast",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blk_next_bio",
        "block/bounce.c:__blk_queue_bounce",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583954560,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584346272,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:433",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/mpage.c:mpage_alloc",
        "fs/mpage.c:mpage_alloc",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_alloc_ioend",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:io_submit_init_bio",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/bio.c:bio_clone_fast",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_map_kern",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_copy_user_iov",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:__blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-crypto-fallback.c:blk_crypto_clone_bio",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584346272,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584462992,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:437",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/mpage.c:mpage_alloc",
        "fs/mpage.c:mpage_alloc",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_alloc_ioend",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:io_submit_init_bio",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/bio.c:bio_clone_fast",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_map_kern",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_copy_user_iov",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:__blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-crypto-fallback.c:blk_crypto_clone_bio",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584462992,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, short unsigned int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584497440,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:398",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/mpage.c:mpage_alloc",
        "fs/mpage.c:mpage_alloc",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/bio.c:bio_clone_fast",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584497440,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, short unsigned int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584907520,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:431",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_alloc",
        "fs/mpage.c:mpage_alloc",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/fops.c:__blkdev_direct_IO",
        "block/bio.c:bio_clone_fast",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584907520,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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
struct bio * bio_alloc_bioset(struct block_device * bdev, short unsigned int nr_vecs, unsigned int opf, gfp_t gfp_mask, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585607136,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:470",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/fops.c:__blkdev_direct_IO_async",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:__blkdev_direct_IO",
        "block/bio.c:bio_split",
        "block/bio.c:blk_next_bio",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585607136,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1263
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
struct bio * bio_alloc_bioset(struct block_device * bdev, short unsigned int nr_vecs, blk_opf_t opf, gfp_t gfp_mask, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586375936,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:493",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/fops.c:__blkdev_direct_IO_async",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:__blkdev_direct_IO",
        "block/bio.c:bio_split",
        "block/bio.c:blk_next_bio",
        "block/blk-map.c:blk_rq_map_bio_alloc",
        "drivers/md/md.c:md_super_write",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586375936,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1321
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
struct bio * bio_alloc_bioset(struct block_device * bdev, short unsigned int nr_vecs, blk_opf_t opf, gfp_t gfp_mask, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586622256,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:492",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/fops.c:__blkdev_direct_IO_async",
        "block/bio.c:bio_split",
        "block/bio.c:blk_next_bio",
        "block/blk-map.c:blk_rq_map_bio_alloc",
        "drivers/md/md.c:md_super_write",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586622256,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1321
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
struct bio * bio_alloc_bioset(struct block_device * bdev, short unsigned int nr_vecs, blk_opf_t opf, gfp_t gfp_mask, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586893760,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:492",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_read_folio",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/fops.c:__blkdev_direct_IO_async",
        "block/bio.c:bio_split",
        "block/bio.c:blk_next_bio",
        "block/blk-map.c:blk_rq_map_bio_alloc",
        "drivers/md/md.c:md_super_write",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586893760,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1321
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495776160,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:429",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_clone_fast",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blk_next_bio",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495776160,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229128132,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:429",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/mpage.c:mpage_alloc",
        "fs/mpage.c:mpage_alloc",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_clone_fast",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blk_next_bio",
        "block/bounce.c:__blk_queue_bounce",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/dm.c:alloc_tio",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229128132,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289950384,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:429",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/mpage.c:mpage_alloc",
        "fs/mpage.c:mpage_alloc",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_clone_fast",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blk_next_bio",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289950384,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274920968,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:429",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/mpage.c:mpage_alloc",
        "fs/mpage.c:mpage_alloc",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_clone_fast",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blk_next_bio",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274920968,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583923296,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:429",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swap_read_pages",
        "kernel/power/swap.c:swap_read_pages",
        "kernel/power/swap.c:write_page",
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_clone_fast",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blk_next_bio",
        "block/bounce.c:__blk_queue_bounce",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583923296,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583860240,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:429",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_clone_fast",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blk_next_bio",
        "block/bounce.c:__blk_queue_bounce",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860240,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583907056,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:429",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_clone_fast",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blk_next_bio",
        "block/bounce.c:__blk_queue_bounce",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583907056,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
struct bio * bio_alloc_bioset(gfp_t gfp_mask, unsigned int nr_iovecs, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_bioset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584008320,
      "name": "bio_alloc_bioset",
      "external": true,
      "loc": "block/bio.c:429",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_clone_fast",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blk_next_bio",
        "block/bounce.c:__blk_queue_bounce",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008320,
      "name": "bio_alloc_bioset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int nr_iovecs</code> ➡️ <code>unsigned int nr_iovecs</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int nr_iovecs</code> ➡️ <code>short unsigned int nr_iovecs</code>
</li>
</ul>
</details>
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
<code>struct block_device * bdev</code>
</li>
<li>
<b>Param added. </b>
<code>short unsigned int nr_vecs</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int opf</code>
</li>
<li>
<b>Param removed. </b>
<code>short unsigned int nr_iovecs</code>
</li>
<li>
<b>Param reordered. </b>
<code>gfp_mask, nr_iovecs, bs</code> ➡️ <code>bdev, nr_vecs, opf, gfp_mask, bs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int opf</code> ➡️ <code>blk_opf_t opf</code>
</li>
</ul>
</details>
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
