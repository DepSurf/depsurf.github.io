# Function: <code>bio_endio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582723744,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1743",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-map.c:blk_rq_map_user_iov",
        "block/blk-mq.c:blk_sq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "drivers/block/brd.c:brd_make_request",
        "drivers/block/xen-blkfront.c:split_bio_end",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_make_request",
        "drivers/md/md.c:md_make_request",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582723744,
      "name": "bio_endio",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582995840,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1742",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-map.c:blk_rq_map_user_iov",
        "block/blk-mq.c:blk_sq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "drivers/block/brd.c:brd_make_request",
        "drivers/block/xen-blkfront.c:split_bio_end",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_make_request",
        "drivers/md/md.c:md_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582995840,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583100832,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1797",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-map.c:blk_rq_map_user_iov",
        "block/blk-mq.c:blk_sq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "drivers/block/xen-blkfront.c:split_bio_end",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_make_request",
        "drivers/md/md.c:md_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583100832,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583160800,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1808",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-map.c:blk_rq_map_user_iov",
        "block/blk-mq.c:blk_mq_make_request",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_make_request",
        "drivers/md/md.c:md_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583160800,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583336656,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1772",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-mq.c:blk_mq_make_request",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583336656,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583545888,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1829",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-mq.c:blk_mq_make_request",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_make_request",
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583545888,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583663424,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1759",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-mq.c:blk_mq_make_request",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583663424,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583851456,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1796",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-mq.c:blk_mq_make_request",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583851456,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583953392,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1838",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-mq.c:blk_mq_make_request",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_make_request",
        "drivers/md/md.c:md_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583953392,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584345632,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1414",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/iomap/buffered-io.c:iomap_submit_ioend",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "block/blk-crypto.c:__blk_crypto_bio_prep",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-stripe.c:stripe_map_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584345632,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584462384,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1417",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/iomap/buffered-io.c:iomap_submit_ioend",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:__submit_bio_noacct_mq",
        "block/blk-core.c:__submit_bio_noacct_mq",
        "block/blk-core.c:__submit_bio_noacct",
        "block/blk-core.c:__submit_bio_noacct",
        "block/blk-core.c:submit_bio_checks",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "block/blk-crypto.c:__blk_crypto_bio_prep",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_submit_bio",
        "drivers/md/md.c:md_submit_bio",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-stripe.c:stripe_map_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584462384,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584496832,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1380",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/iomap/buffered-io.c:iomap_submit_ioend",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:__submit_bio_noacct",
        "block/blk-core.c:__submit_bio_noacct",
        "block/blk-core.c:submit_bio_checks",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "block/blk-crypto.c:__blk_crypto_bio_prep",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_submit_bio",
        "drivers/md/md.c:md_submit_bio",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584496832,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584905616,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1462",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_submit_ioend",
        "block/fops.c:__blkdev_direct_IO",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:submit_bio_checks",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "block/blk-crypto.c:__blk_crypto_bio_prep",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "drivers/md/md.c:md_end_io_acct",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_submit_bio",
        "drivers/md/md.c:md_submit_bio",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_io_dec_pending",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584905616,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585605264,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1521",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_submit_ioend",
        "block/fops.c:__blkdev_direct_IO",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:submit_bio_noacct",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_get_new_requests",
        "block/blk-mq.c:blk_mq_end_request_batch",
        "block/blk-mq.c:blk_update_request",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "block/blk-crypto.c:__blk_crypto_bio_prep",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "drivers/md/md.c:md_end_io_acct",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_submit_bio",
        "drivers/md/md.c:md_submit_bio",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_io_complete",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585605264,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586373648,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1584",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_submit_ioend",
        "block/fops.c:__blkdev_direct_IO",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:submit_bio_noacct",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-merge.c:bio_split_rw",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_get_new_requests",
        "block/blk-mq.c:blk_mq_end_request_batch",
        "block/blk-mq.c:blk_update_request",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "block/blk-crypto.c:__blk_crypto_bio_prep",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "drivers/md/md.c:md_end_io_acct",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_submit_bio",
        "drivers/md/md.c:md_submit_bio",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:__dm_io_complete",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586373648,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586620128,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1569",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_submit_ioend",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:submit_bio_noacct",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-merge.c:bio_split_rw",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_get_new_requests",
        "block/blk-mq.c:blk_mq_end_request_batch",
        "block/blk-mq.c:blk_update_request",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "block/blk-crypto.c:__blk_crypto_bio_prep",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "drivers/md/md.c:md_end_io_acct",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_submit_bio",
        "drivers/md/md.c:md_submit_bio",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:__dm_io_complete",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586620128,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586891584,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1576",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_submit_ioend",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:submit_bio_noacct",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-merge.c:bio_split_rw",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_end_request_batch",
        "block/blk-mq.c:blk_update_request",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "block/blk-crypto.c:__blk_crypto_bio_prep",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "drivers/md/md.c:md_end_clone_io",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_submit_bio",
        "drivers/md/md.c:md_submit_bio",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:__dm_io_complete",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586891584,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495774744,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1838",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-mq.c:blk_mq_make_request",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_make_request",
        "drivers/md/md.c:md_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495774744,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229126940,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1838",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-mq.c:blk_mq_make_request",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_make_request",
        "drivers/md/md.c:md_make_request",
        "drivers/md/md.c:md_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229126940,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289947744,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1838",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-mq.c:blk_mq_make_request",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_make_request",
        "drivers/md/md.c:md_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289947744,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274919780,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1838",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-mq.c:blk_mq_make_request",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_make_request",
        "drivers/md/md.c:md_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274919780,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583922128,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1838",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-mq.c:blk_mq_make_request",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "drivers/nvme/host/multipath.c:nvme_ns_head_make_request",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_make_request",
        "drivers/md/md.c:md_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922128,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583859088,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1838",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-mq.c:blk_mq_make_request",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "drivers/nvdimm/pmem.c:pmem_make_request",
        "drivers/nvdimm/btt.c:btt_make_request",
        "drivers/nvme/host/multipath.c:nvme_ns_head_make_request",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_make_request",
        "drivers/md/md.c:md_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583859088,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583905888,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1838",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-mq.c:blk_mq_make_request",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_make_request",
        "drivers/md/md.c:md_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583905888,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void bio_endio(struct bio * bio)
```

```json
{
  "name": "bio_endio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584007152,
      "name": "bio_endio",
      "external": true,
      "loc": "block/bio.c:1838",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_direct_IO",
        "block/bio.c:bio_chain_endio",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-mq.c:blk_mq_make_request",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_verify_fn",
        "block/bio-integrity.c:bio_integrity_prep",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_submit_flush_data",
        "drivers/md/md.c:md_make_request",
        "drivers/md/md.c:md_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-stripe.c:stripe_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584007152,
      "name": "bio_endio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
