# Function: <code>io_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_schedule",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587367926,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:431",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:bit_wait_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581252211,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:431",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582749090,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:431",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582806716,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:431",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:bt_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582870199,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:431",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585797343,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:431",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_completion"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_schedule",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587868742,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:446",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:bit_wait_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581419808,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:446",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583026685,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:446",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583085804,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:446",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:bt_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583156114,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:446",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586194831,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:446",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_completion"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_schedule",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588083318,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:466",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:bit_wait_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580618998,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:466",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481835,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:466",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581498699,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:466",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581671757,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:466",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_dio_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583131522,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:466",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583178435,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:466",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_poll_hybrid_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583193746,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:466",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583268078,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:466",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583345162,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:466",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_wait",
        "block/blk-wbt.c:wbt_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586399308,
      "name": "io_schedule",
      "external": false,
      "loc": "include/linux/sched.h:466",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_completion"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579578688,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:4993",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap.c:iomap_dio_rw",
        "block/blk-core.c:get_request",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/bsg.c:bsg_release",
        "block/blk-wbt.c:wbt_wait",
        "block/blk-wbt.c:wbt_wait",
        "drivers/md/dm.c:dm_wait_for_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578688,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579608384,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:5038",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap.c:iomap_dio_rw",
        "block/blk-core.c:get_request",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/bsg.c:bsg_release",
        "block/blk-wbt.c:wbt_wait",
        "block/blk-wbt.c:wbt_wait",
        "drivers/md/dm.c:dm_wait_for_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579608384,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579638736,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:5163",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap.c:iomap_dio_rw",
        "block/blk-core.c:get_request",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/bsg.c:bsg_release",
        "block/blk-wbt.c:wbt_wait",
        "block/blk-wbt.c:wbt_wait",
        "drivers/md/dm.c:dm_wait_for_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579638736,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579676416,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:5146",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap.c:iomap_dio_rw",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-rq-qos.c:rq_qos_wait",
        "drivers/md/dm.c:dm_wait_for_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676416,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589956000,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:5599",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-rq-qos.c:rq_qos_wait",
        "drivers/md/dm.c:dm_wait_for_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589956000,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590183664,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:5790",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "drivers/md/dm.c:dm_wait_for_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590183664,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591201088,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:6023",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io",
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/page_io.c:swap_readpage",
        "block/blk-core.c:blk_io_schedule",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "drivers/md/dm.c:dm_wait_for_bios_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591201088,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591696144,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:6843",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io",
        "mm/filemap.c:wait_on_page_bit_common",
        "block/blk-core.c:blk_io_schedule",
        "block/blk-mq.c:blk_mq_poll_hybrid",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "drivers/md/dm.c:dm_wait_for_bios_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591696144,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591638656,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:7194",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io",
        "mm/filemap.c:wait_on_page_bit_common",
        "block/blk-core.c:blk_io_schedule",
        "block/blk-mq.c:blk_mq_poll_hybrid",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591638656,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592812416,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:8392",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io",
        "mm/filemap.c:wait_on_page_bit_common",
        "block/blk-core.c:blk_io_schedule",
        "block/blk-mq.c:blk_mq_poll_hybrid",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592812416,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594714464,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:8683",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:bit_wait_io",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:folio_wait_private_2_killable",
        "mm/filemap.c:folio_wait_private_2",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:folio_wait_bit_common",
        "block/blk-core.c:blk_io_schedule",
        "block/blk-mq.c:blk_mq_poll_hybrid",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594714464,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596461568,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:8867",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:bit_wait_io",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:folio_wait_bit_common",
        "block/blk-core.c:blk_io_schedule",
        "block/blk-mq.c:blk_mq_poll_hybrid",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "drivers/md/dm.c:dm_wait_for_bios_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596461568,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597003280,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:9024",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:bit_wait_io",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:folio_wait_bit_common",
        "block/blk-core.c:blk_io_schedule",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "drivers/md/dm.c:dm_wait_for_bios_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597003280,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597932480,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:9019",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:bit_wait_io",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:folio_wait_bit_common",
        "block/blk-core.c:blk_io_schedule",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "drivers/md/dm.c:dm_wait_for_bios_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597932480,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503926920,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:5790",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io",
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "drivers/md/dm.c:dm_wait_for_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503926920,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236536820,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:5790",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "drivers/md/dm.c:dm_wait_for_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236536820,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297774848,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:5790",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "drivers/md/dm.c:dm_wait_for_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297774848,
      "name": "io_schedule",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279795594,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:5790",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "drivers/md/dm.c:dm_wait_for_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279795594,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589785952,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:5790",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "drivers/md/dm.c:dm_wait_for_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589785952,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589508496,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:5790",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "drivers/md/dm.c:dm_wait_for_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589508496,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590229360,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:5790",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "drivers/md/dm.c:dm_wait_for_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590229360,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void io_schedule()
```

```json
{
  "name": "io_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590279952,
      "name": "io_schedule",
      "external": true,
      "loc": "kernel/sched/core.c:5790",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:bit_wait_io",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "drivers/md/dm.c:dm_wait_for_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590279952,
      "name": "io_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void io_schedule()
```
</details>
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
