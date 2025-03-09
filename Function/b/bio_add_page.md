# Function: <code>bio_add_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582712416,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:806",
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
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/crypto.c:ext4_encrypted_zeroout",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:md_super_write",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582712416,
      "name": "bio_add_page",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582989488,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:809",
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
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/crypto.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:md_super_write",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582989488,
      "name": "bio_add_page",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583094064,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:814",
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
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/crypto.c:fscrypt_zeroout_range",
        "fs/iomap.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/blk-lib.c:__blkdev_issue_zeroout",
        "block/blk-zoned.c:blkdev_report_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583094064,
      "name": "bio_add_page",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583150448,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:830",
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
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/blk-lib.c:__blkdev_issue_zeroout",
        "block/blk-zoned.c:blkdev_report_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583150448,
      "name": "bio_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583325600,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:833",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap.c:iomap_dio_zero",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-zoned.c:blkdev_report_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583325600,
      "name": "bio_add_page",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583534464,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:893",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-zoned.c:blkdev_report_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583534464,
      "name": "bio_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583657952,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:819",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583657952,
      "name": "bio_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583848368,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:822",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583848368,
      "name": "bio_add_page",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583950480,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:861",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583950480,
      "name": "bio_add_page",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584341040,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:933",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:do_region",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584341040,
      "name": "bio_add_page",
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
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584458672,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:933",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:do_region",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584458672,
      "name": "bio_add_page",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584493440,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:922",
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
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:do_region",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584493440,
      "name": "bio_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584901344,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:1005",
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
        "fs/iomap/buffered-io.c:iomap_readpage_iter",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:do_region",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584901344,
      "name": "bio_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585610077,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:1084",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_add_folio"
      ],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585601424,
      "name": "bio_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586380013,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:1136",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_add_folio"
      ],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:__swap_writepage",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:md_super_write",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586369520,
      "name": "bio_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586616048,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:1093",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586616048,
      "name": "bio_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586886624,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:1094",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "drivers/md/dm-io.c:do_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586886624,
      "name": "bio_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495768312,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:861",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495768312,
      "name": "bio_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229122568,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:861",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229122568,
      "name": "bio_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289942304,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:861",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289942304,
      "name": "bio_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274915564,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:861",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274915564,
      "name": "bio_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583919216,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:861",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swap_read_pages",
        "kernel/power/swap.c:write_page",
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583919216,
      "name": "bio_add_page",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583856176,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:861",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583856176,
      "name": "bio_add_page",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583902976,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:861",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583902976,
      "name": "bio_add_page",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int bio_add_page(struct bio * bio, struct page * page, unsigned int len, unsigned int offset)
```

```json
{
  "name": "bio_add_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584004224,
      "name": "bio_add_page",
      "external": true,
      "loc": "block/bio.c:861",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:get_swap_bio",
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584004224,
      "name": "bio_add_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
