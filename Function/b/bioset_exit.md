# Function: <code>bioset_exit</code>

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
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583536848,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1950",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583536848,
      "name": "bioset_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583659824,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1882",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583659824,
      "name": "bioset_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1916",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583858488,
      "name": "bioset_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583846640,
      "name": "bioset_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583948784,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1958",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583948784,
      "name": "bioset_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584345109,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1537",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bioset_init"
      ],
      "caller_func": [
        "block/blk-core.c:__blk_alloc_queue",
        "block/blk-sysfs.c:__blk_release_queue",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:__bind_mempools",
        "drivers/md/dm.c:__bind_mempools",
        "drivers/md/dm.c:__bind_mempools",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584339456,
      "name": "bioset_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584461861,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1540",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bioset_init"
      ],
      "caller_func": [
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-sysfs.c:blk_release_queue",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:__bind_mempools",
        "drivers/md/dm.c:__bind_mempools",
        "drivers/md/dm.c:__bind_mempools",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584457200,
      "name": "bioset_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584492144,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1503",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-sysfs.c:blk_release_queue",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584492144,
      "name": "bioset_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584906032,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1587",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-sysfs.c:blk_release_queue",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/md/md.c:acct_bioset_exit",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584906032,
      "name": "bioset_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585605728,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1645",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-sysfs.c:blk_release_queue",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/md/md.c:acct_bioset_exit",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585605728,
      "name": "bioset_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586374432,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1708",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/md/md.c:acct_bioset_exit",
        "drivers/md/md.c:md_free_disk",
        "drivers/md/md.c:md_free_disk",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586374432,
      "name": "bioset_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586620912,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1693",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/md/md.c:acct_bioset_exit",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586620912,
      "name": "bioset_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586892368,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1700",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:__bind",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586892368,
      "name": "bioset_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495769224,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1958",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495769224,
      "name": "bioset_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229120864,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1958",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229120864,
      "name": "bioset_exit",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289940304,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1958",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289940304,
      "name": "bioset_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274914436,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1958",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274914436,
      "name": "bioset_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583917520,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1958",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583917520,
      "name": "bioset_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583854480,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1958",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583854480,
      "name": "bioset_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583901280,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1958",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583901280,
      "name": "bioset_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void bioset_exit(struct bio_set * bs)
```

```json
{
  "name": "bioset_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584002432,
      "name": "bioset_exit",
      "external": true,
      "loc": "block/bio.c:1958",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584002432,
      "name": "bioset_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void bioset_exit(struct bio_set * bs)
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
