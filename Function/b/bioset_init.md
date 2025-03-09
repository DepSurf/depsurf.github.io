# Function: <code>bioset_init</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583537104,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1987",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_init",
        "block/bio.c:init_bio",
        "block/bio.c:bioset_init_from_src",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583537104,
      "name": "bioset_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
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
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583660080,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1919",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_init",
        "block/bio.c:init_bio",
        "block/bio.c:bioset_init_from_src",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/bounce.c:init_emergency_isa_pool",
        "block/bounce.c:init_emergency_isa_pool",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583660080,
      "name": "bioset_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
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
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583846864,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1953",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_init",
        "block/bio.c:init_bio",
        "block/bio.c:bioset_init_from_src",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/bounce.c:init_emergency_isa_pool",
        "block/bounce.c:init_emergency_isa_pool",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583846864,
      "name": "bioset_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583949024,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1995",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_init",
        "block/bio.c:init_bio",
        "block/bio.c:bioset_init_from_src",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/bounce.c:init_emergency_isa_pool",
        "block/bounce.c:init_emergency_isa_pool",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583949024,
      "name": "bioset_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584344816,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1574",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_init",
        "fs/iomap/buffered-io.c:iomap_init",
        "block/bio.c:init_bio",
        "block/bio.c:bioset_init_from_src",
        "block/blk-core.c:__blk_alloc_queue",
        "block/bounce.c:init_bounce_bioset",
        "block/bounce.c:init_bounce_bioset",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584344816,
      "name": "bioset_init",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584461568,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1577",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_init",
        "fs/iomap/buffered-io.c:iomap_init",
        "block/bio.c:init_bio",
        "block/bio.c:bioset_init_from_src",
        "block/blk-core.c:blk_alloc_queue",
        "block/bounce.c:init_bounce_bioset",
        "block/bounce.c:init_bounce_bioset",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584461568,
      "name": "bioset_init",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584494512,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1540",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_init",
        "fs/iomap/buffered-io.c:iomap_init",
        "block/bio.c:init_bio",
        "block/bio.c:bioset_init_from_src",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584494512,
      "name": "bioset_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584906464,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1625",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_init",
        "block/fops.c:blkdev_init",
        "block/bio.c:init_bio",
        "block/bio.c:bioset_init_from_src",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584906464,
      "name": "bioset_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 670
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
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585606160,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1683",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_init",
        "block/fops.c:blkdev_init",
        "block/bio.c:init_bio",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585606160,
      "name": "bioset_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586374864,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1746",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_init",
        "block/fops.c:blkdev_init",
        "block/bio.c:init_bio",
        "block/genhd.c:__alloc_disk_node",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_alloc_md_mempools",
        "drivers/md/dm-table.c:dm_table_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586374864,
      "name": "bioset_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586621344,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1731",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_init",
        "block/fops.c:blkdev_init",
        "block/bio.c:init_bio",
        "block/genhd.c:__alloc_disk_node",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_alloc_md_mempools",
        "drivers/md/dm-table.c:dm_table_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586621344,
      "name": "bioset_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586892800,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1738",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_init",
        "block/fops.c:blkdev_init",
        "block/bio.c:init_bio",
        "block/genhd.c:__alloc_disk_node",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_alloc_md_mempools",
        "drivers/md/dm-table.c:dm_table_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586892800,
      "name": "bioset_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 691
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
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495769480,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1995",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_init",
        "block/bio.c:init_bio",
        "block/bio.c:bioset_init_from_src",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495769480,
      "name": "bioset_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229121268,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1995",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_init",
        "block/bio.c:init_bio",
        "block/bio.c:bioset_init_from_src",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229121268,
      "name": "bioset_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
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
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289940976,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1995",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_init",
        "block/bio.c:init_bio",
        "block/bio.c:bioset_init_from_src",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289940976,
      "name": "bioset_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 972
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
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274914686,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1995",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_init",
        "block/bio.c:init_bio",
        "block/bio.c:bioset_init_from_src",
        "block/blk-core.c:blk_alloc_queue_node",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274914686,
      "name": "bioset_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583917760,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1995",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_init",
        "block/bio.c:init_bio",
        "block/bio.c:bioset_init_from_src",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/bounce.c:init_emergency_isa_pool",
        "block/bounce.c:init_emergency_isa_pool",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583917760,
      "name": "bioset_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583854720,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1995",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_init",
        "block/bio.c:init_bio",
        "block/bio.c:bioset_init_from_src",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/bounce.c:init_emergency_isa_pool",
        "block/bounce.c:init_emergency_isa_pool",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583854720,
      "name": "bioset_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583901520,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1995",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_init",
        "block/bio.c:init_bio",
        "block/bio.c:bioset_init_from_src",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/bounce.c:init_emergency_isa_pool",
        "block/bounce.c:init_emergency_isa_pool",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583901520,
      "name": "bioset_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```

```json
{
  "name": "bioset_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584002672,
      "name": "bioset_init",
      "external": true,
      "loc": "block/bio.c:1995",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_init",
        "block/bio.c:init_bio",
        "block/bio.c:bioset_init_from_src",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/bounce.c:init_emergency_isa_pool",
        "block/bounce.c:init_emergency_isa_pool",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584002672,
      "name": "bioset_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int bioset_init(struct bio_set * bs, unsigned int pool_size, unsigned int front_pad, int flags)
```
</details>
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
