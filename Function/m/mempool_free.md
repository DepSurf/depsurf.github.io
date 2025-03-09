# Function: <code>mempool_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580484112,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:392",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_alloc",
        "block/bio-integrity.c:bio_integrity_free",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_destroy",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/scsi/scsi_lib.c:scsi_sg_free",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:free_rq_clone",
        "drivers/md/dm.c:free_rq_clone",
        "drivers/md/dm.c:dm_requeue_original_request",
        "drivers/md/dm.c:dm_softirq_done",
        "drivers/md/dm.c:dm_prep_fn",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580484112,
      "name": "mempool_free",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580566048,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:388",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job",
        "drivers/md/dm-rq.c:dm_old_prep_fn",
        "drivers/md/dm-rq.c:dm_old_prep_fn",
        "drivers/md/dm-rq.c:dm_softirq_done",
        "drivers/md/dm-rq.c:dm_requeue_original_request",
        "drivers/md/dm-rq.c:free_rq_clone",
        "drivers/md/dm-rq.c:free_rq_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580566048,
      "name": "mempool_free",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580632448,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:388",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/blk-core.c:__blk_put_request",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job",
        "drivers/md/dm-rq.c:dm_old_prep_fn",
        "drivers/md/dm-rq.c:dm_old_prep_fn",
        "drivers/md/dm-rq.c:dm_softirq_done",
        "drivers/md/dm-rq.c:dm_requeue_original_request",
        "drivers/md/dm-rq.c:free_rq_clone",
        "drivers/md/dm-rq.c:free_rq_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580632448,
      "name": "mempool_free",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580660112,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:388",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/blk-core.c:__blk_put_request",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap_put",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580660112,
      "name": "mempool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580745104,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:389",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/blk-core.c:__blk_put_request",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580745104,
      "name": "mempool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580880112,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:443",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/blk-core.c:__blk_put_request",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580880112,
      "name": "mempool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580953424,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:444",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580953424,
      "name": "mempool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581048688,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:452",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581048688,
      "name": "mempool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581104352,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:452",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581104352,
      "name": "mempool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581287008,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:452",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "block/blk-crypto.c:__blk_crypto_free_request",
        "block/blk-crypto.c:__bio_crypt_free_ctx",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:rebalance",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/md/md.c:md_end_io",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287008,
      "name": "mempool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581330480,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:450",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "block/blk-crypto.c:__blk_crypto_free_request",
        "block/blk-crypto.c:__bio_crypt_free_ctx",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:rebalance",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/md/md.c:md_end_io",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581330480,
      "name": "mempool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581349808,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:450",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "block/blk-crypto.c:__blk_crypto_free_request",
        "block/blk-crypto.c:__bio_crypt_free_ctx",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:rebalance",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581349808,
      "name": "mempool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581597552,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:452",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "block/blk-crypto.c:__blk_crypto_free_request",
        "block/blk-crypto.c:__bio_crypt_free_ctx",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:rebalance",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581597552,
      "name": "mempool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581955312,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:451",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:sio_read_complete",
        "mm/page_io.c:sio_write_complete",
        "fs/notify/fanotify/fanotify.c:fanotify_free_event",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "block/blk-crypto.c:__blk_crypto_free_request",
        "block/blk-crypto.c:__bio_crypt_free_ctx",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:rebalance",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581955312,
      "name": "mempool_free",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582387696,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:457",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:sio_read_complete",
        "mm/page_io.c:sio_write_complete",
        "fs/notify/fanotify/fanotify.c:fanotify_free_event",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "block/blk-crypto.c:__blk_crypto_free_request",
        "block/blk-crypto.c:__bio_crypt_free_ctx",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:rebalance",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582387696,
      "name": "mempool_free",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582593456,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:457",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:sio_read_complete",
        "mm/page_io.c:sio_write_complete",
        "fs/notify/fanotify/fanotify.c:fanotify_free_event",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "block/blk-crypto.c:__blk_crypto_free_request",
        "block/blk-crypto.c:__bio_crypt_free_ctx",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:rebalance",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582593456,
      "name": "mempool_free",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582764640,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:504",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:sio_read_complete",
        "mm/page_io.c:sio_write_complete",
        "fs/notify/fanotify/fanotify.c:fanotify_free_event",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "block/blk-crypto.c:__blk_crypto_free_request",
        "block/blk-crypto.c:__bio_crypt_free_ctx",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_endio",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:rebalance",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582764640,
      "name": "mempool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492472224,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:452",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492472224,
      "name": "mempool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226345872,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:452",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226345872,
      "name": "mempool_free",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285752864,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:452",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap_put",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/md/dm-io.c:complete_io",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285752864,
      "name": "mempool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272539204,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:452",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap_put",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/md/dm-io.c:complete_io",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272539204,
      "name": "mempool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581073200,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:452",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/nvme/host/pci.c:nvme_unmap_data",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581073200,
      "name": "mempool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581020384,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:452",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/nvme/host/pci.c:nvme_unmap_data",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581020384,
      "name": "mempool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581064400,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:452",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581064400,
      "name": "mempool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void mempool_free(void * element, mempool_t * pool)
```

```json
{
  "name": "mempool_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581125952,
      "name": "mempool_free",
      "external": true,
      "loc": "mm/mempool.c:452",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:verity_work",
        "fs/ext4/readpage.c:__read_end_io",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_free",
        "block/bounce.c:bounce_end_io",
        "block/bio-integrity.c:bio_integrity_free",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:__btree_for_each",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:btree_remove_level",
        "lib/btree.c:merge",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_destroy",
        "lib/sg_pool.c:sg_pool_free",
        "lib/sg_pool.c:sg_pool_free",
        "drivers/dma/dmaengine.c:dmaengine_unmap",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/scsi/sd.c:sd_uninit_command",
        "drivers/md/dm-io.c:dec_count",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125952,
      "name": "mempool_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
