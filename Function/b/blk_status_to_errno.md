# Function: <code>blk_status_to_errno</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583192835,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:168",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "kernel/power/swap.c:hib_wait_io",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/bio.c:bio_endio",
        "block/bio.c:submit_bio_wait_endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583176448,
      "name": "blk_status_to_errno",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583351376,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:168",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_wait_io",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/bio.c:bio_endio",
        "block/bio.c:submit_bio_wait",
        "block/blk-core.c:blk_update_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583351376,
      "name": "blk_status_to_errno",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583553648,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:241",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_wait_io",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/bio.c:bio_endio",
        "block/bio.c:submit_bio_wait",
        "block/blk-core.c:blk_update_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583553648,
      "name": "blk_status_to_errno",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583674272,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:159",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_wait_io",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap.c:iomap_dio_bio_end_io",
        "fs/iomap.c:iomap_read_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/bio.c:bio_endio",
        "block/bio.c:submit_bio_wait",
        "block/blk-core.c:blk_update_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583674272,
      "name": "blk_status_to_errno",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583870288,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:197",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_wait_io",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/bio.c:bio_endio",
        "block/bio.c:submit_bio_wait",
        "block/blk-core.c:blk_update_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583870288,
      "name": "blk_status_to_errno",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583982825,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:200",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "kernel/power/swap.c:hib_wait_io",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/bio.c:bio_endio",
        "block/bio.c:submit_bio_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583973168,
      "name": "blk_status_to_errno",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584364410,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:208",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete"
      ],
      "caller_func": [
        "kernel/power/swap.c:hib_wait_io",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_bio_complete",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap/buffered-io.c:iomap_writepage_end_bio",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/bio.c:submit_bio_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584360384,
      "name": "blk_status_to_errno",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584482894,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:211",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete"
      ],
      "caller_func": [
        "kernel/power/swap.c:hib_wait_io",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_bio_complete",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap/buffered-io.c:iomap_writepage_end_bio",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/bio.c:submit_bio_wait",
        "drivers/md/md.c:super_written"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584476784,
      "name": "blk_status_to_errno",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584517284,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:212",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete"
      ],
      "caller_func": [
        "kernel/power/swap.c:hib_wait_io",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_bio_complete",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap/buffered-io.c:iomap_writepage_end_bio",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/bio.c:submit_bio_wait",
        "drivers/md/md.c:super_written"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584511680,
      "name": "blk_status_to_errno",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584927540,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:207",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete"
      ],
      "caller_func": [
        "kernel/power/swap.c:hib_wait_io",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_bio_complete",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap/buffered-io.c:iomap_writepage_end_bio",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/bio.c:submit_bio_wait",
        "drivers/md/md.c:super_written"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584923104,
      "name": "blk_status_to_errno",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585623660,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:192",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_rq_completion",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_completion"
      ],
      "caller_func": [
        "kernel/power/swap.c:hib_wait_io",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_bio_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap/buffered-io.c:iomap_writepage_end_bio",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/bio.c:submit_bio_wait",
        "drivers/md/md.c:super_written"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585620048,
      "name": "blk_status_to_errno",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586394073,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:190",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_rq_completion",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_completion"
      ],
      "caller_func": [
        "kernel/power/swap.c:hib_wait_io",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_bio_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap/buffered-io.c:iomap_writepage_end_bio",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/bio.c:submit_bio_wait",
        "drivers/md/md.c:super_written"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586390192,
      "name": "blk_status_to_errno",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586640886,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:193",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_rq_completion",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_completion"
      ],
      "caller_func": [
        "kernel/power/swap.c:hib_wait_io",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_bio_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq",
        "fs/mpage.c:mpage_write_end_io",
        "fs/mpage.c:mpage_read_end_io",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/iomap/buffered-io.c:iomap_writepage_end_bio",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/bio.c:submit_bio_wait",
        "drivers/block/virtio_blk.c:virtblk_report_zones",
        "drivers/md/md.c:super_written"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586636992,
      "name": "blk_status_to_errno",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586911846,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:194",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_rq_completion",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_completion"
      ],
      "caller_func": [
        "kernel/power/swap.c:hib_wait_io",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_bio_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq",
        "fs/mpage.c:mpage_write_end_io",
        "fs/mpage.c:mpage_read_end_io",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/iomap/buffered-io.c:iomap_writepage_end_bio",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "block/fops.c:blkdev_bio_end_io_async",
        "block/fops.c:blkdev_bio_end_io",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/bio.c:submit_bio_wait",
        "drivers/block/virtio_blk.c:virtblk_report_zones",
        "drivers/md/md.c:super_written"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586907872,
      "name": "blk_status_to_errno",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495807412,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:200",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/bio.c:bio_endio",
        "block/bio.c:submit_bio_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495792296,
      "name": "blk_status_to_errno",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229147740,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:200",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:hib_wait_io",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/bio.c:bio_endio",
        "block/bio.c:submit_bio_wait",
        "block/blk-core.c:blk_update_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229147740,
      "name": "blk_status_to_errno",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289992940,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:200",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/bio.c:bio_endio",
        "block/bio.c:submit_bio_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289978992,
      "name": "blk_status_to_errno",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274945434,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:200",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/bio.c:bio_endio",
        "block/bio.c:submit_bio_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274937114,
      "name": "blk_status_to_errno",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583951561,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:200",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "kernel/power/swap.c:hib_wait_io",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/bio.c:bio_endio",
        "block/bio.c:submit_bio_wait",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/core.c:nvme_alloc_ns_head",
        "drivers/nvme/host/core.c:nvme_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583941904,
      "name": "blk_status_to_errno",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583888489,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:200",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "kernel/power/swap.c:hib_wait_io",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/bio.c:bio_endio",
        "block/bio.c:submit_bio_wait",
        "drivers/nvdimm/pmem.c:pmem_rw_page",
        "drivers/nvdimm/pmem.c:pmem_rw_page",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/core.c:nvme_alloc_ns_head",
        "drivers/nvme/host/core.c:nvme_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583878848,
      "name": "blk_status_to_errno",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583935321,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:200",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "kernel/power/swap.c:hib_wait_io",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/bio.c:bio_endio",
        "block/bio.c:submit_bio_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583925664,
      "name": "blk_status_to_errno",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int blk_status_to_errno(blk_status_t status)
```

```json
{
  "name": "blk_status_to_errno",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584037081,
      "name": "blk_status_to_errno",
      "external": true,
      "loc": "block/blk-core.c:200",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "kernel/power/swap.c:hib_wait_io",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/mpage.c:mpage_end_io",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/ext4/page-io.c:ext4_end_bio",
        "block/bio.c:bio_endio",
        "block/bio.c:submit_bio_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584027056,
      "name": "blk_status_to_errno",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int blk_status_to_errno(blk_status_t status)
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
