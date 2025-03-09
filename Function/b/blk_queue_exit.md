# Function: <code>blk_queue_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582751845,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:670",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_read_page",
        "fs/block_dev.c:bdev_write_page",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582752432,
      "name": "blk_queue_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583029829,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:672",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "fs/dax.c:__dax_zero_page_range",
        "fs/dax.c:dax_fault",
        "fs/dax.c:dax_fault",
        "fs/dax.c:dax_do_io",
        "fs/dax.c:dax_do_io",
        "fs/dax.c:read_dax_sector",
        "fs/dax.c:dax_map_atomic",
        "block/blk-timeout.c:blk_timeout_work",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583030384,
      "name": "blk_queue_exit",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583134597,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:673",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:__dax_zero_page_range",
        "fs/dax.c:read_dax_sector",
        "fs/dax.c:dax_map_atomic",
        "block/blk-timeout.c:blk_timeout_work",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583135152,
      "name": "blk_queue_exit",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583191272,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:793",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-timeout.c:blk_timeout_work",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583192080,
      "name": "blk_queue_exit",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583368512,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:867",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:__blk_put_request",
        "block/blk-core.c:blk_get_request_flags"
      ],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583368624,
      "name": "blk_queue_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583578144,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:964",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:__blk_put_request",
        "block/blk-core.c:blk_get_request"
      ],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583578272,
      "name": "blk_queue_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583690717,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:445",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:generic_make_request"
      ],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_get_request",
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583690848,
      "name": "blk_queue_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583879372,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:443",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:direct_make_request"
      ],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_get_request",
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583879488,
      "name": "blk_queue_exit",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583982428,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:447",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:direct_make_request"
      ],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_get_request",
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583982544,
      "name": "blk_queue_exit",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584370597,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:476",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:direct_make_request"
      ],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584372096,
      "name": "blk_queue_exit",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584487624,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:494",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:__submit_bio_noacct_mq",
        "block/blk-core.c:__submit_bio_noacct"
      ],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584488416,
      "name": "blk_queue_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584521474,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:495",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:__submit_bio_noacct"
      ],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584523072,
      "name": "blk_queue_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584929083,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:502",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:__submit_bio"
      ],
      "caller_func": [
        "block/bdev.c:bdev_write_page",
        "block/bdev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584933312,
      "name": "blk_queue_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585636156,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:396",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:bio_poll",
        "block/blk-core.c:bio_poll",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": [
        "block/bdev.c:bdev_write_page",
        "block/bdev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_get_new_requests",
        "block/blk-mq.c:blk_mq_get_new_requests",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585631952,
      "name": "blk_queue_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586407393,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:374",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:bio_poll",
        "block/blk-core.c:bio_poll",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": [
        "block/bdev.c:bdev_write_page",
        "block/bdev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_get_new_requests",
        "block/blk-mq.c:blk_mq_get_new_requests",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586403200,
      "name": "blk_queue_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586654797,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:371",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:bio_poll",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_rq_poll",
        "block/blk-mq.c:blk_mq_get_new_requests",
        "block/blk-mq.c:blk_mq_get_new_requests",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586650368,
      "name": "blk_queue_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586926058,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:373",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:bio_poll",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_rq_poll",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586921536,
      "name": "blk_queue_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495806808,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:447",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:direct_make_request"
      ],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_get_request",
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495807000,
      "name": "blk_queue_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229158492,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:447",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request"
      ],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_get_request",
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229158648,
      "name": "blk_queue_exit",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289992200,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:447",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:direct_make_request"
      ],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_get_request",
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289992464,
      "name": "blk_queue_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274944984,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:447",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:direct_make_request"
      ],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_get_request",
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274945132,
      "name": "blk_queue_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583951164,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:447",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:direct_make_request"
      ],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_get_request",
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583951280,
      "name": "blk_queue_exit",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583888092,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:447",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:direct_make_request"
      ],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_get_request",
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583888208,
      "name": "blk_queue_exit",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583934924,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:447",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:direct_make_request"
      ],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_get_request",
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583935040,
      "name": "blk_queue_exit",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_exit(struct request_queue * q)
```

```json
{
  "name": "blk_queue_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584036556,
      "name": "blk_queue_exit",
      "external": true,
      "loc": "block/blk-core.c:447",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:direct_make_request"
      ],
      "caller_func": [
        "fs/block_dev.c:bdev_write_page",
        "fs/block_dev.c:bdev_read_page",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_get_request",
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584036704,
      "name": "blk_queue_exit",
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
