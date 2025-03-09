# Function: <code>bio_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582718880,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:538",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "mm/page_io.c:end_swap_bio_write",
        "mm/page_io.c:end_swap_bio_read",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/ext4/page-io.c:ext4_release_io_end",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_io_submit",
        "fs/ext4/readpage.c:completion_pages",
        "fs/ext4/readpage.c:mpage_end_io",
        "fs/ext4/crypto.c:ext4_encrypted_zeroout",
        "fs/ext4/crypto.c:ext4_encrypted_zeroout",
        "fs/ext4/crypto.c:ext4_encrypted_zeroout",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_clone_bioset",
        "block/bio.c:bio_uncopy_user",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern_endio",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-lib.c:bio_batch_end_io",
        "block/blk-lib.c:bio_batch_end_io",
        "block/bounce.c:bounce_end_io",
        "drivers/lightnvm/core.c:nvm_submit_ppa",
        "drivers/block/virtio_blk.c:virtblk_serial_show",
        "drivers/block/xen-blkfront.c:split_bio_end",
        "drivers/block/xen-blkfront.c:split_bio_end",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:end_clone_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582718880,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582995792,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:537",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/crypto.c:completion_pages",
        "fs/crypto/crypto.c:fscrypt_zeroout_range",
        "fs/crypto/crypto.c:fscrypt_zeroout_range",
        "fs/crypto/crypto.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/readpage.c:mpage_end_io",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern_endio",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user",
        "block/bio.c:bio_clone_bioset",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_map_user_iov",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/bounce.c:bounce_end_io",
        "drivers/lightnvm/core.c:__nvm_submit_ppa",
        "drivers/block/xen-blkfront.c:split_bio_end",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582995792,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583100784,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:541",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/crypto.c:completion_pages",
        "fs/crypto/crypto.c:fscrypt_zeroout_range",
        "fs/crypto/crypto.c:fscrypt_zeroout_range",
        "fs/crypto/crypto.c:fscrypt_zeroout_range",
        "fs/iomap.c:iomap_dio_actor",
        "fs/iomap.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/readpage.c:mpage_end_io",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern_endio",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user",
        "block/bio.c:bio_clone_bioset",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_map_user_iov",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/bounce.c:bounce_end_io",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_report_zones",
        "drivers/lightnvm/core.c:__nvm_submit_ppa",
        "drivers/block/xen-blkfront.c:split_bio_end",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583100784,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583156848,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:555",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:completion_pages",
        "fs/iomap.c:iomap_dio_actor",
        "fs/iomap.c:iomap_dio_bio_end_io",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end",
        "fs/ext4/readpage.c:mpage_end_io",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern_endio",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user",
        "block/bio.c:bio_clone_bioset",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_map_user_iov",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/bounce.c:bounce_end_io",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_report_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583156848,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583331904,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:555",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:completion_pages",
        "fs/iomap.c:iomap_dio_actor",
        "fs/iomap.c:iomap_dio_bio_end_io",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end",
        "fs/ext4/readpage.c:mpage_end_io",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern_endio",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user",
        "block/bio.c:bio_clone_bioset",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/bounce.c:bounce_end_io",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_report_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583331904,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583541056,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:556",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:completion_pages",
        "fs/iomap.c:iomap_dio_actor",
        "fs/iomap.c:iomap_dio_bio_end_io",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end",
        "fs/ext4/readpage.c:mpage_end_io",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern_endio",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user",
        "block/bio.c:bio_clone_bioset",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/bounce.c:bounce_end_io",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_report_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583541056,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583663376,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:558",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:completion_pages",
        "fs/iomap.c:iomap_dio_bio_actor",
        "fs/iomap.c:iomap_dio_bio_end_io",
        "fs/iomap.c:iomap_read_end_io",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end",
        "fs/ext4/readpage.c:mpage_end_io",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern_endio",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/bounce.c:blk_queue_bounce",
        "block/bounce.c:bounce_end_io",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583663376,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583851408,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:546",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:completion_pages",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end",
        "fs/ext4/readpage.c:mpage_end_io",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern_endio",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/bounce.c:__blk_queue_bounce",
        "block/bounce.c:bounce_end_io",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583851408,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583953344,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:598",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:completion_pages",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern_endio",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/bounce.c:__blk_queue_bounce",
        "block/bounce.c:bounce_end_io",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583953344,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584345456,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:645",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end",
        "fs/ext4/readpage.c:__read_end_io",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:__blk_rq_unmap_user",
        "block/blk-map.c:__blk_rq_unmap_user",
        "block/blk-map.c:__blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-map.c:bio_copy_kern_endio_read",
        "block/blk-map.c:bio_map_kern",
        "block/blk-map.c:bio_map_kern_endio",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_copy_user_iov",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/bounce.c:bounce_end_io",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584345456,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584462208,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:647",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end",
        "fs/ext4/readpage.c:__read_end_io",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-map.c:bio_copy_kern_endio_read",
        "block/blk-map.c:bio_map_kern",
        "block/blk-map.c:bio_map_kern_endio",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_copy_user_iov",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/bounce.c:bounce_end_io",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584462208,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584496656,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:602",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end",
        "fs/ext4/readpage.c:__read_end_io",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_copy_kern_endio_read",
        "block/blk-map.c:bio_map_kern_endio",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_copy_user_iov",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584496656,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584905232,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:678",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end",
        "fs/ext4/readpage.c:__read_end_io",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_bio_read",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:blkdev_bio_end_io",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:bio_copy_kern_endio_read",
        "block/blk-map.c:bio_map_kern_endio",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_copy_user_iov",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "drivers/md/md.c:md_end_io_acct",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:dm_io_dec_pending",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584905232,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585604880,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:736",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end",
        "fs/ext4/readpage.c:__read_end_io",
        "block/fops.c:__blkdev_direct_IO_async",
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:blkdev_bio_end_io",
        "block/bio.c:bio_split",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_chain_endio",
        "block/blk-lib.c:blkdev_issue_secure_erase",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-mq.c:blk_rq_prep_clone",
        "block/blk-mq.c:blk_rq_prep_clone",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated",
        "drivers/md/md.c:md_end_io_acct",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:dm_io_complete",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585604880,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586375611,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:799",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_dirty_fn"
      ],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end",
        "fs/ext4/readpage.c:__read_end_io",
        "block/fops.c:__blkdev_direct_IO_async",
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:blkdev_bio_end_io",
        "block/bio.c:bio_split",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_chain_endio",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_map_user_iov",
        "block/blk-map.c:blk_rq_map_user_iov",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-lib.c:blkdev_issue_secure_erase",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-mq.c:blk_rq_prep_clone",
        "block/blk-mq.c:blk_rq_prep_clone",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated",
        "drivers/md/md.c:md_end_io_acct",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:__dm_io_complete",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586373552,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586619888,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:798",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/mpage.c:mpage_write_end_io",
        "fs/mpage.c:mpage_read_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end",
        "fs/ext4/readpage.c:__read_end_io",
        "fs/squashfs/block.c:squashfs_bio_read_cached",
        "block/fops.c:__blkdev_direct_IO_async",
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:blkdev_bio_end_io",
        "block/bio.c:bio_split",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_chain_endio",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_map_user_iov",
        "block/blk-map.c:blk_rq_map_user_iov",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-lib.c:blkdev_issue_secure_erase",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-mq.c:blk_rq_prep_clone",
        "block/blk-mq.c:blk_rq_prep_clone",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated",
        "drivers/md/md.c:md_end_io_acct",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:__dm_io_complete",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586619888,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586890912,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:798",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/mpage.c:mpage_write_end_io",
        "fs/mpage.c:mpage_read_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt",
        "fs/iomap/buffered-io.c:iomap_finish_ioend",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end",
        "fs/ext4/readpage.c:__read_end_io",
        "fs/squashfs/block.c:squashfs_bio_read_cached",
        "block/fops.c:__blkdev_direct_IO_async",
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:blkdev_bio_end_io",
        "block/bio.c:bio_split",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_chain_endio",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_map_user_iov",
        "block/blk-map.c:blk_rq_map_user_iov",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-lib.c:blkdev_issue_secure_erase",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-mq.c:blk_rq_prep_clone",
        "block/blk-mq.c:blk_rq_prep_clone",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated",
        "drivers/md/md.c:md_end_clone_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:__dm_io_complete",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586890912,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495774624,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:598",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:completion_pages",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern_endio",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495774624,
      "name": "bio_put",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229126840,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:598",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:completion_pages",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern_endio",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/bounce.c:__blk_queue_bounce",
        "block/bounce.c:bounce_end_io",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229126840,
      "name": "bio_put",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289947616,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:598",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:completion_pages",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern_endio",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289947616,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274919692,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:598",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:completion_pages",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern_endio",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274919692,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583922080,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:598",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swap_read_pages",
        "kernel/power/swap.c:swap_read_pages",
        "kernel/power/swap.c:swap_read_pages",
        "kernel/power/swap.c:write_page",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:completion_pages",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern_endio",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/bounce.c:__blk_queue_bounce",
        "block/bounce.c:bounce_end_io",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922080,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583859040,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:598",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:completion_pages",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern_endio",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/bounce.c:__blk_queue_bounce",
        "block/bounce.c:bounce_end_io",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583859040,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583905840,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:598",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:completion_pages",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern_endio",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/bounce.c:__blk_queue_bounce",
        "block/bounce.c:bounce_end_io",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583905840,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void bio_put(struct bio * bio)
```

```json
{
  "name": "bio_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584007104,
      "name": "bio_put",
      "external": true,
      "loc": "block/bio.c:598",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io",
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write",
        "fs/buffer.c:end_bio_bh_io_sync",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:completion_pages",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_endio",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern_endio",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_uncopy_user",
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-core.c:blk_rq_prep_clone",
        "block/blk-flush.c:blkdev_issue_flush",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_unmap_user",
        "block/blk-map.c:blk_rq_append_bio",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/bounce.c:__blk_queue_bounce",
        "block/bounce.c:bounce_end_io",
        "block/blk-zoned.c:blkdev_reset_zones",
        "block/blk-zoned.c:blkdev_reset_zones",
        "drivers/md/md.c:sync_page_io",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-io.c:endio",
        "drivers/md/dm-rq.c:end_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584007104,
      "name": "bio_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
