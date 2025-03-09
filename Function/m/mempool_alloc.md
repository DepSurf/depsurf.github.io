# Function: <code>mempool_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580483200,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:315",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/crypto.c:ext4_encrypt",
        "fs/ext4/crypto.c:ext4_encrypted_zeroout",
        "block/bio.c:bvec_alloc",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/blk-core.c:get_request",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/scsi_lib.c:scsi_sg_alloc",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dm_prep_fn",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580483200,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580565552,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:311",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_zeroout_range",
        "fs/crypto/crypto.c:fscrypt_encrypt_page",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/blk-core.c:get_request",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy",
        "drivers/md/dm-rq.c:dm_old_prep_fn",
        "drivers/md/dm-rq.c:dm_old_prep_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580565552,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580631952,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:311",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_zeroout_range",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/blk-core.c:get_request",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy",
        "drivers/md/dm-rq.c:dm_old_prep_fn",
        "drivers/md/dm-rq.c:dm_old_prep_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580631952,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580659584,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:311",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/blk-core.c:get_request",
        "block/bounce.c:blk_queue_bounce",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580659584,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580744560,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:312",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/blk-core.c:get_request",
        "block/bounce.c:blk_queue_bounce",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580744560,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580880368,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:366",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/blk-core.c:get_request",
        "block/bounce.c:blk_queue_bounce",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580880368,
      "name": "mempool_alloc",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580953680,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:367",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/bounce.c:blk_queue_bounce",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:md_flush_request",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580953680,
      "name": "mempool_alloc",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581048928,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:375",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/bounce.c:__blk_queue_bounce",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581048928,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581104592,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:375",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/bounce.c:__blk_queue_bounce",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581104592,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581287232,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:375",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/bounce.c:__blk_queue_bounce",
        "block/bio-integrity.c:bio_integrity_alloc",
        "block/blk-crypto.c:__blk_crypto_rq_bio_prep",
        "block/blk-crypto.c:__bio_crypt_clone",
        "block/blk-crypto.c:bio_crypt_set_ctx",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/sg_pool.c:sg_pool_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_unmap_cmnd",
        "drivers/md/md.c:md_make_request",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287232,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581331248,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:373",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/bounce.c:__blk_queue_bounce",
        "block/bio-integrity.c:bio_integrity_alloc",
        "block/blk-crypto.c:__blk_crypto_rq_bio_prep",
        "block/blk-crypto.c:__bio_crypt_clone",
        "block/blk-crypto.c:bio_crypt_set_ctx",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/sg_pool.c:sg_pool_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_unmap_cmnd",
        "drivers/md/md.c:md_submit_bio",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581331248,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581350576,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:373",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/bio-integrity.c:bio_integrity_alloc",
        "block/blk-crypto.c:__blk_crypto_rq_bio_prep",
        "block/blk-crypto.c:__bio_crypt_clone",
        "block/blk-crypto.c:bio_crypt_set_ctx",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/sg_pool.c:sg_pool_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_unmap_cmnd",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581350576,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581597776,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:375",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/bio-integrity.c:bio_integrity_alloc",
        "block/blk-crypto.c:__blk_crypto_rq_bio_prep",
        "block/blk-crypto.c:__bio_crypt_clone",
        "block/blk-crypto.c:bio_crypt_set_ctx",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/sg_pool.c:sg_pool_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581597776,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581955616,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:374",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage_fs",
        "mm/page_io.c:__swap_writepage",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/bio-integrity.c:bio_integrity_alloc",
        "block/blk-crypto.c:__blk_crypto_rq_bio_prep",
        "block/blk-crypto.c:__bio_crypt_clone",
        "block/blk-crypto.c:bio_crypt_set_ctx",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/sg_pool.c:sg_pool_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581955616,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582388080,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:380",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage_fs",
        "mm/page_io.c:swap_writepage_fs",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/bio-integrity.c:bio_integrity_alloc",
        "block/blk-crypto.c:__blk_crypto_rq_bio_prep",
        "block/blk-crypto.c:__bio_crypt_clone",
        "block/blk-crypto.c:bio_crypt_set_ctx",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/sg_pool.c:sg_pool_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582388080,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582593840,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:380",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage_fs",
        "mm/page_io.c:swap_writepage_fs",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/bio-integrity.c:bio_integrity_alloc",
        "block/blk-crypto.c:__blk_crypto_rq_bio_prep",
        "block/blk-crypto.c:__bio_crypt_clone",
        "block/blk-crypto.c:bio_crypt_set_ctx",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/sg_pool.c:sg_pool_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/virtio_scsi.c:virtscsi_abort",
        "drivers/scsi/virtio_scsi.c:virtscsi_device_reset",
        "drivers/scsi/sd.c:sd_set_special_bvec",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582593840,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582765024,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:390",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_read_folio_fs",
        "mm/page_io.c:swap_writepage_fs",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_event",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/bio-integrity.c:bio_integrity_alloc",
        "block/blk-crypto.c:__blk_crypto_rq_bio_prep",
        "block/blk-crypto.c:__bio_crypt_clone",
        "block/blk-crypto.c:bio_crypt_set_ctx",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/virtio_scsi.c:virtscsi_abort",
        "drivers/scsi/virtio_scsi.c:virtscsi_device_reset",
        "drivers/scsi/sd.c:sd_set_special_bvec",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582765024,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492472496,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:375",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492472496,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226346200,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:375",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/bounce.c:__blk_queue_bounce",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:btree_node_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226346200,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285752352,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:375",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285752352,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272539572,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:375",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/btree.c:btree_insert_level",
        "lib/btree.c:btree_insert_level",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272539572,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581073440,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:375",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/bounce.c:__blk_queue_bounce",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581073440,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581020624,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:375",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/bounce.c:__blk_queue_bounce",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581020624,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581064640,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:375",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/bounce.c:__blk_queue_bounce",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/virtio_scsi.c:virtscsi_abort",
        "drivers/scsi/virtio_scsi.c:virtscsi_device_reset",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581064640,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
void * mempool_alloc(mempool_t * pool, gfp_t gfp_mask)
```

```json
{
  "name": "mempool_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581126192,
      "name": "mempool_alloc",
      "external": true,
      "loc": "mm/mempool.c:375",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bio_alloc_bioset",
        "block/bio.c:bvec_alloc",
        "block/bounce.c:__blk_queue_bounce",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "lib/sg_pool.c:sg_pool_alloc",
        "drivers/dma/dmaengine.c:dmaengine_get_unmap_data",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581126192,
      "name": "mempool_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
