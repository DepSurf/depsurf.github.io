# Function: <code>submit_bio_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int submit_bio_wait(int rw, struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582712992,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:868",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/ext4/crypto.c:ext4_encrypted_zeroout",
        "block/blk-flush.c:blkdev_issue_flush",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582712992,
      "name": "submit_bio_wait",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582990064,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:870",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/crypto/crypto.c:fscrypt_zeroout_range",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582990064,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583094928,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:924",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/crypto/crypto.c:fscrypt_zeroout_range",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_report_zones",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583094928,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583151616,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:940",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_report_zones",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583151616,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583326736,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:939",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_report_zones",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583326736,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583535584,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:997",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_report_zones",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583535584,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583658704,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:921",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap.c:iomap_read_page_sync",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583658704,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583845408,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:980",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583845408,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583947456,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:1019",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583947456,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584339072,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:1143",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584339072,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584456816,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:1146",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584456816,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584491920,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:1146",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584491920,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584900784,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:1240",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584900784,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585600688,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:1308",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_read_folio_sync",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_secure_erase",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585600688,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586368624,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:1371",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_read_folio_sync",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_secure_erase",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586368624,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586615280,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:1356",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_readpage_bdev_sync",
        "mm/page_io.c:swap_writepage_bdev_sync",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_read_folio_sync",
        "fs/squashfs/block.c:squashfs_bio_read",
        "fs/squashfs/block.c:squashfs_bio_read_cached",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_secure_erase",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586615280,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586885664,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:1368",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:swap_read_folio_bdev_sync",
        "mm/page_io.c:swap_writepage_bdev_sync",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_read_folio_sync",
        "fs/squashfs/block.c:squashfs_bio_read",
        "fs/squashfs/block.c:squashfs_bio_read_cached",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_secure_erase",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586885664,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495767424,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:1019",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495767424,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229120356,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:1019",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229120356,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289939600,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:1019",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289939600,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274914022,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:1019",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274914022,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583916192,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:1019",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swap_read_pages",
        "kernel/power/swap.c:hib_submit_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583916192,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583853248,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:1019",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583853248,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583899952,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:1019",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583899952,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int submit_bio_wait(struct bio * bio)
```

```json
{
  "name": "submit_bio_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584000992,
      "name": "submit_bio_wait",
      "external": true,
      "loc": "block/bio.c:1019",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584000992,
      "name": "submit_bio_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
