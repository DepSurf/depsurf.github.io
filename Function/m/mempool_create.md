# Function: <code>mempool_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580484608,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:179",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/crypto.c:ext4_init_crypto",
        "block/bio.c:__bioset_create",
        "block/bio.c:__bioset_create",
        "block/bounce.c:init_emergency_isa_pool",
        "lib/btree.c:btree_init",
        "drivers/scsi/scsi_lib.c:scsi_init_queue",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580484608,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580566528,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:175",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bioset_create",
        "block/bio.c:__bioset_create",
        "block/bounce.c:init_emergency_isa_pool",
        "lib/btree.c:btree_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580566528,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580632928,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:175",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_initialize",
        "block/bio.c:__bioset_create",
        "block/bio.c:__bioset_create",
        "block/bounce.c:init_emergency_isa_pool",
        "lib/btree.c:btree_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580632928,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580660576,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:175",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_initialize",
        "block/bio.c:bioset_create",
        "block/bio.c:bioset_create",
        "block/bounce.c:init_emergency_isa_pool",
        "lib/btree.c:btree_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580660576,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580745616,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:176",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_initialize",
        "block/bio.c:bioset_create",
        "block/bio.c:bioset_create",
        "block/bounce.c:init_emergency_isa_pool",
        "lib/btree.c:btree_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580745616,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580881376,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:248",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_initialize",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881376,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580954688,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:249",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_initialize",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954688,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581049920,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:253",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_initialize",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581049920,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581105584,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:253",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_initialize",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105584,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581288688,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:253",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_initialize",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "block/blk-crypto.c:bio_crypt_ctx_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dmaengine_init_unmap_pool",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288688,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581332272,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:251",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_initialize",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "block/blk-crypto.c:bio_crypt_ctx_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dmaengine_init_unmap_pool",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581332272,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581351568,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:251",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_initialize",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "block/blk-crypto.c:bio_crypt_ctx_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351568,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581598912,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:253",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_initialize",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "block/blk-crypto.c:bio_crypt_ctx_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581598912,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581956848,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:252",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:sio_pool_init",
        "fs/crypto/crypto.c:fscrypt_initialize",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "block/blk-crypto.c:bio_crypt_ctx_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956848,
      "name": "mempool_create",
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582389408,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:258",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:sio_pool_init",
        "fs/crypto/crypto.c:fscrypt_initialize",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "block/blk-crypto.c:bio_crypt_ctx_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582389408,
      "name": "mempool_create",
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582595168,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:258",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:sio_pool_init",
        "fs/crypto/crypto.c:fscrypt_initialize",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "block/blk-crypto.c:bio_crypt_ctx_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/scsi/virtio_scsi.c:virtio_scsi_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582595168,
      "name": "mempool_create",
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582766384,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:268",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:sio_pool_init",
        "fs/crypto/crypto.c:fscrypt_initialize",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "block/blk-crypto.c:bio_crypt_ctx_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/scsi/virtio_scsi.c:virtio_scsi_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582766384,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492471216,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:253",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_initialize",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492471216,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226347192,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:253",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_initialize",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226347192,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285754064,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:253",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_initialize",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285754064,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272540636,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:253",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_initialize",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272540636,
      "name": "mempool_create",
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581074432,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:253",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_initialize",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074432,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581021616,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:253",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_initialize",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021616,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581065632,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:253",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_initialize",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/scsi/virtio_scsi.c:init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065632,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
mempool_t * mempool_create(int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581127184,
      "name": "mempool_create",
      "external": true,
      "loc": "mm/mempool.c:253",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_initialize",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "lib/btree.c:btree_init",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581127184,
      "name": "mempool_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
