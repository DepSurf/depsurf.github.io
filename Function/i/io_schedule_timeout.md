# Function: <code>io_schedule_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587362976,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:4774",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:bit_wait_io",
        "kernel/sched/wait.c:bit_wait_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io",
        "mm/mempool.c:mempool_alloc",
        "mm/backing-dev.c:congestion_wait",
        "mm/backing-dev.c:wait_iff_congested",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "block/blk-core.c:get_request",
        "block/blk-mq-tag.c:bt_get",
        "block/bsg.c:bsg_release",
        "drivers/md/dm.c:dm_wait_for_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587362976,
      "name": "io_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587864480,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:5025",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:bit_wait_io_timeout",
        "kernel/sched/wait.c:bit_wait_io",
        "kernel/sched/completion.c:wait_for_completion_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io",
        "mm/mempool.c:mempool_alloc",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "block/blk-core.c:get_request",
        "block/blk-mq-tag.c:bt_get",
        "block/bsg.c:bsg_release",
        "drivers/md/dm.c:dm_wait_for_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587864480,
      "name": "io_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588079168,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:5064",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:bit_wait_io_timeout",
        "kernel/sched/wait.c:bit_wait_io",
        "kernel/sched/completion.c:wait_for_completion_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/mempool.c:mempool_alloc",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap.c:iomap_dio_rw",
        "block/blk-core.c:get_request",
        "block/blk-mq.c:blk_mq_poll_hybrid_sleep",
        "block/bsg.c:bsg_release",
        "block/blk-wbt.c:wbt_wait",
        "block/blk-wbt.c:wbt_wait",
        "drivers/md/dm.c:dm_wait_for_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588079168,
      "name": "io_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588308816,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:4980",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io",
        "mm/mempool.c:mempool_alloc",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588308816,
      "name": "io_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588874176,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:5025",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588874176,
      "name": "io_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589252992,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:5150",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589252992,
      "name": "io_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589495216,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:5133",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589495216,
      "name": "io_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589955920,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:5586",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589955920,
      "name": "io_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590183584,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:5777",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590183584,
      "name": "io_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591199216,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:6010",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "block/blk-core.c:blk_io_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591199216,
      "name": "io_schedule_timeout",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591694112,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:6830",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "block/blk-core.c:blk_io_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591694112,
      "name": "io_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591636608,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:7181",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "block/blk-core.c:blk_io_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591636608,
      "name": "io_schedule_timeout",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592810656,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:8379",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait",
        "block/blk-core.c:blk_io_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592810656,
      "name": "io_schedule_timeout",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594712496,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:8670",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:bit_wait_io_timeout",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "block/blk-core.c:blk_io_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594712496,
      "name": "io_schedule_timeout",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596459504,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:8854",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:bit_wait_io_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_io_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_io",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "block/blk-core.c:blk_io_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596459504,
      "name": "io_schedule_timeout",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597000864,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:9011",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:bit_wait_io_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_io_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_io",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "block/blk-core.c:blk_io_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597000864,
      "name": "io_schedule_timeout",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597930256,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:9006",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:bit_wait_io_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_io_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_io",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "block/blk-core.c:blk_io_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597930256,
      "name": "io_schedule_timeout",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503926848,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:5777",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503926848,
      "name": "io_schedule_timeout",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236536748,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:5777",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236536748,
      "name": "io_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297774736,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:5777",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297774736,
      "name": "io_schedule_timeout",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279795522,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:5777",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279795522,
      "name": "io_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589785872,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:5777",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589785872,
      "name": "io_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589508416,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:5777",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589508416,
      "name": "io_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590229280,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:5777",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590229280,
      "name": "io_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
long int io_schedule_timeout(long int timeout)
```

```json
{
  "name": "io_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590279872,
      "name": "io_schedule_timeout",
      "external": true,
      "loc": "kernel/sched/core.c:5777",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io_timeout",
        "kernel/sched/completion.c:wait_for_completion_io",
        "mm/mempool.c:mempool_alloc",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/backing-dev.c:wait_iff_congested",
        "mm/backing-dev.c:congestion_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590279872,
      "name": "io_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
