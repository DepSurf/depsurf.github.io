# Function: <code>blk_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool blk_poll(struct request_queue * q, blk_qc_t cookie)
```

```json
{
  "name": "blk_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582759824,
      "name": "blk_poll",
      "external": true,
      "loc": "block/blk-core.c:3328",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582759824,
      "name": "blk_poll",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool blk_poll(struct request_queue * q, blk_qc_t cookie)
```

```json
{
  "name": "blk_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583037856,
      "name": "blk_poll",
      "external": true,
      "loc": "block/blk-core.c:3300",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583037856,
      "name": "blk_poll",
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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool blk_poll(struct request_queue * q, blk_qc_t cookie)
```

```json
{
  "name": "blk_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583376176,
      "name": "blk_poll",
      "external": true,
      "loc": "block/blk-core.c:2429",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583376176,
      "name": "blk_poll",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool blk_poll(struct request_queue * q, blk_qc_t cookie)
```

```json
{
  "name": "blk_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583585648,
      "name": "blk_poll",
      "external": true,
      "loc": "block/blk-core.c:2572",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583585648,
      "name": "blk_poll",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blk_poll(struct request_queue * q, blk_qc_t cookie, bool spin)
```

```json
{
  "name": "blk_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583731024,
      "name": "blk_poll",
      "external": true,
      "loc": "block/blk-mq.c:3436",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731024,
      "name": "blk_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 831
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
int blk_poll(struct request_queue * q, blk_qc_t cookie, bool spin)
```

```json
{
  "name": "blk_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583917792,
      "name": "blk_poll",
      "external": true,
      "loc": "block/blk-mq.c:3471",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_iopoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583917792,
      "name": "blk_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 841
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
int blk_poll(struct request_queue * q, blk_qc_t cookie, bool spin)
```

```json
{
  "name": "blk_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584021072,
      "name": "blk_poll",
      "external": true,
      "loc": "block/blk-mq.c:3490",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_iopoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584021072,
      "name": "blk_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 818
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int blk_poll(struct request_queue * q, blk_qc_t cookie, bool spin)
```

```json
{
  "name": "blk_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584411280,
      "name": "blk_poll",
      "external": true,
      "loc": "block/blk-mq.c:3711",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_await_one",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_iopoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584411280,
      "name": "blk_poll.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
    },
    {
      "addr": 18446744071584412064,
      "name": "blk_poll",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int blk_poll(struct request_queue * q, blk_qc_t cookie, bool spin)
```

```json
{
  "name": "blk_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584533824,
      "name": "blk_poll",
      "external": true,
      "loc": "block/blk-mq.c:3841",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:dio_await_one",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_iopoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584533824,
      "name": "blk_poll.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    },
    {
      "addr": 18446744071584534192,
      "name": "blk_poll",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int blk_poll(struct request_queue * q, blk_qc_t cookie, bool spin)
```

```json
{
  "name": "blk_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584566240,
      "name": "blk_poll",
      "external": true,
      "loc": "block/blk-mq.c:3903",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_iopoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584566240,
      "name": "blk_poll.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    },
    {
      "addr": 18446744071584566608,
      "name": "blk_poll",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int blk_poll(struct request_queue * q, blk_qc_t cookie, bool spin)
```

```json
{
  "name": "blk_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584977200,
      "name": "blk_poll",
      "external": true,
      "loc": "block/blk-mq.c:3960",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_iopoll",
        "block/fops.c:__blkdev_direct_IO",
        "block/fops.c:blkdev_iopoll",
        "block/fops.c:__blkdev_direct_IO_simple",
        "block/blk-exec.c:blk_execute_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584977200,
      "name": "blk_poll.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    },
    {
      "addr": 18446744071584977568,
      "name": "blk_poll",
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int blk_poll(struct request_queue * q, blk_qc_t cookie, bool spin)
```

```json
{
  "name": "blk_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495847504,
      "name": "blk_poll",
      "external": true,
      "loc": "block/blk-mq.c:3490",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_iopoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495847504,
      "name": "blk_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
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
int blk_poll(struct request_queue * q, blk_qc_t cookie, bool spin)
```

```json
{
  "name": "blk_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229200732,
      "name": "blk_poll",
      "external": true,
      "loc": "block/blk-mq.c:3490",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_iopoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229200732,
      "name": "blk_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 860
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
int blk_poll(struct request_queue * q, blk_qc_t cookie, bool spin)
```

```json
{
  "name": "blk_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290048288,
      "name": "blk_poll",
      "external": true,
      "loc": "block/blk-mq.c:3490",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_iopoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290048288,
      "name": "blk_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 996
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
int blk_poll(struct request_queue * q, blk_qc_t cookie, bool spin)
```

```json
{
  "name": "blk_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274980976,
      "name": "blk_poll",
      "external": true,
      "loc": "block/blk-mq.c:3490",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_iopoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274980976,
      "name": "blk_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
int blk_poll(struct request_queue * q, blk_qc_t cookie, bool spin)
```

```json
{
  "name": "blk_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583989808,
      "name": "blk_poll",
      "external": true,
      "loc": "block/blk-mq.c:3490",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_iopoll",
        "drivers/nvme/host/core.c:__nvme_submit_sync_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583989808,
      "name": "blk_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 818
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
int blk_poll(struct request_queue * q, blk_qc_t cookie, bool spin)
```

```json
{
  "name": "blk_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583925664,
      "name": "blk_poll",
      "external": true,
      "loc": "block/blk-mq.c:3490",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_iopoll",
        "drivers/nvme/host/core.c:__nvme_submit_sync_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583925664,
      "name": "blk_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 818
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
int blk_poll(struct request_queue * q, blk_qc_t cookie, bool spin)
```

```json
{
  "name": "blk_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583973568,
      "name": "blk_poll",
      "external": true,
      "loc": "block/blk-mq.c:3490",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_iopoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583973568,
      "name": "blk_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 818
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
int blk_poll(struct request_queue * q, blk_qc_t cookie, bool spin)
```

```json
{
  "name": "blk_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584077376,
      "name": "blk_poll",
      "external": true,
      "loc": "block/blk-mq.c:3490",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:swap_readpage",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_iopoll",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_iopoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584077376,
      "name": "blk_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 818
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
bool blk_poll(struct request_queue * q, blk_qc_t cookie)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
bool blk_poll(struct request_queue * q, blk_qc_t cookie)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool spin</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int blk_poll(struct request_queue * q, blk_qc_t cookie, bool spin)
```
</details>
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
