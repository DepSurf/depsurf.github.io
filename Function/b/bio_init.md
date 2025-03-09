# Function: <code>bio_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_init(struct bio * bio)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582712336,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:269",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_alloc_bioset"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582712336,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_init(struct bio * bio)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582994935,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:273",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_alloc_bioset"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582989408,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_init(struct bio * bio, struct bio_vec * table, short unsigned int max_vecs)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583099863,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:273",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_alloc_bioset"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583093968,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void bio_init(struct bio * bio, struct bio_vec * table, short unsigned int max_vecs)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583150640,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:277",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583150640,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void bio_init(struct bio * bio, struct bio_vec * table, short unsigned int max_vecs)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583325792,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:277",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583325792,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void bio_init(struct bio * bio, struct bio_vec * table, short unsigned int max_vecs)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583534560,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:277",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583534560,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void bio_init(struct bio * bio, struct bio_vec * table, short unsigned int max_vecs)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583658048,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:279",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/iomap.c:iomap_read_page_sync",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583658048,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void bio_init(struct bio * bio, struct bio_vec * table, short unsigned int max_vecs)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583844784,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:267",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583844784,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void bio_init(struct bio * bio, struct bio_vec * table, short unsigned int max_vecs)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583946816,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:270",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583946816,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_init(struct bio * bio, struct bio_vec * table, short unsigned int max_vecs)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584346480,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:274",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_alloc_bioset"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584338400,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_init(struct bio * bio, struct bio_vec * table, short unsigned int max_vecs)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584463208,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:278",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_alloc_bioset"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/dm.c:__send_empty_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584455920,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_init(struct bio * bio, struct bio_vec * table, short unsigned int max_vecs)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584496383,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:246",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_kmalloc",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "block/blk-flush.c:blkdev_issue_flush",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm.c:__send_empty_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584491008,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_init(struct bio * bio, struct bio_vec * table, short unsigned int max_vecs)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584904275,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:251",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_kmalloc",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset"
      ],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/blk-flush.c:blkdev_issue_flush",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm.c:__send_empty_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584899616,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void bio_init(struct bio * bio, struct block_device * bdev, struct bio_vec * table, short unsigned int max_vecs, unsigned int opf)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585604372,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:241",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_init_clone",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset"
      ],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_read_folio_sync",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_copy_user_iov",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm.c:__send_empty_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585599616,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void bio_init(struct bio * bio, struct block_device * bdev, struct bio_vec * table, short unsigned int max_vecs, blk_opf_t opf)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586372708,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:247",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_init_clone",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset"
      ],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_read_folio_sync",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_bio_alloc",
        "block/blk-map.c:bio_copy_user_iov",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm.c:__send_empty_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586367504,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_init(struct bio * bio, struct block_device * bdev, struct bio_vec * table, short unsigned int max_vecs, blk_opf_t opf)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586619044,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:246",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_init_clone",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset"
      ],
      "caller_func": [
        "mm/page_io.c:swap_readpage_bdev_sync",
        "mm/page_io.c:swap_writepage_bdev_sync",
        "fs/iomap/buffered-io.c:iomap_read_folio_sync",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_copy_kern",
        "block/blk-map.c:blk_rq_map_bio_alloc",
        "block/blk-map.c:bio_copy_user_iov",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm.c:__send_empty_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586614160,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void bio_init(struct bio * bio, struct block_device * bdev, struct bio_vec * table, short unsigned int max_vecs, blk_opf_t opf)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586889812,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:246",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_init_clone",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset"
      ],
      "caller_func": [
        "mm/page_io.c:swap_read_folio_bdev_sync",
        "mm/page_io.c:swap_writepage_bdev_sync",
        "fs/iomap/buffered-io.c:iomap_read_folio_sync",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_copy_kern",
        "block/blk-map.c:blk_rq_map_bio_alloc",
        "block/blk-map.c:bio_copy_user_iov",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/dm.c:__send_empty_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586884224,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void bio_init(struct bio * bio, struct bio_vec * table, short unsigned int max_vecs)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495767320,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:270",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495767320,
      "name": "bio_init",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void bio_init(struct bio * bio, struct bio_vec * table, short unsigned int max_vecs)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229119468,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:270",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229119468,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void bio_init(struct bio * bio, struct bio_vec * table, short unsigned int max_vecs)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289938800,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:270",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289938800,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void bio_init(struct bio * bio, struct bio_vec * table, short unsigned int max_vecs)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274921072,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:270",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_alloc_bioset"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274913478,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void bio_init(struct bio * bio, struct bio_vec * table, short unsigned int max_vecs)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583915552,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:270",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583915552,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void bio_init(struct bio * bio, struct bio_vec * table, short unsigned int max_vecs)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583852608,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:270",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583852608,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void bio_init(struct bio * bio, struct bio_vec * table, short unsigned int max_vecs)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583899312,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:270",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583899312,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void bio_init(struct bio * bio, struct bio_vec * table, short unsigned int max_vecs)
```

```json
{
  "name": "bio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584000352,
      "name": "bio_init",
      "external": true,
      "loc": "block/bio.c:270",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584000352,
      "name": "bio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bio_vec * table</code>
</li>
<li>
<b>Param added. </b>
<code>short unsigned int max_vecs</code>
</li>
</ul>
</details>
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
<b>Param added. </b>
<code>struct block_device * bdev</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int opf</code>
</li>
<li>
<b>Param reordered. </b>
<code>bio, table, max_vecs</code> ➡️ <code>bio, bdev, table, max_vecs, opf</code>
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
