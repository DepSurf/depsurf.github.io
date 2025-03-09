# Function: <code>blk_queue_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue * q, bool nowait)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582751152,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:649",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_read_page",
        "fs/block_dev.c:bdev_write_page",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582751152,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int blk_queue_enter(struct request_queue * q, bool nowait)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583029152,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:651",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "fs/dax.c:dax_map_atomic",
        "block/blk-timeout.c:blk_timeout_work",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583029152,
      "name": "blk_queue_enter",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue * q, bool nowait)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583133952,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:652",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "fs/dax.c:dax_map_atomic",
        "block/blk-timeout.c:blk_timeout_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583133952,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
int blk_queue_enter(struct request_queue * q, bool nowait)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583190576,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:763",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-timeout.c:blk_timeout_work",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583190576,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583366320,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:818",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:blk_get_request_flags",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583366320,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583575760,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:918",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:blk_get_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583575760,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583688752,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:398",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583688752,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583877584,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:396",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-core.c:direct_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583877584,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583980560,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:400",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-core.c:direct_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583980560,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584369920,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:412",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-core.c:direct_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584369920,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584486016,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:430",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-core.c:__submit_bio_noacct_mq",
        "block/blk-core.c:__submit_bio_noacct",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584486016,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 562
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584520656,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:431",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-core.c:__submit_bio_noacct",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584520656,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 562
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584932944,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:440",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:bdev_write_page",
        "block/bdev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-cgroup.c:blkg_conf_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584932944,
      "name": "blk_queue_enter",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585629824,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:335",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:bdev_write_page",
        "block/bdev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-cgroup.c:blkg_conf_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585629824,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586400992,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:313",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:bdev_write_page",
        "block/bdev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-cgroup.c:blkg_conf_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586400992,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586648112,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:310",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586648112,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586919296,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:312",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586919296,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495804832,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:400",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-core.c:direct_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495804832,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229156492,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:400",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229156492,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289989568,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:400",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-core.c:direct_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289989568,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274943460,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:400",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-core.c:direct_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274943460,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583949296,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:400",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-core.c:direct_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583949296,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583886224,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:400",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-core.c:direct_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583886224,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583933056,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:400",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-core.c:direct_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583933056,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
int blk_queue_enter(struct request_queue * q, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_queue_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584034576,
      "name": "blk_queue_enter",
      "external": true,
      "loc": "block/blk-core.c:400",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-core.c:direct_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584034576,
      "name": "blk_queue_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_mq_req_flags_t flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool nowait</code>
</li>
</ul>
</details>
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
