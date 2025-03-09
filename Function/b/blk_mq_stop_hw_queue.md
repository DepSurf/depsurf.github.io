# Function: <code>blk_mq_stop_hw_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582790064,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:893",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/block/virtio_blk.c:virtio_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582790064,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583067600,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:971",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/block/virtio_blk.c:virtio_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583067600,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583175248,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1030",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583175248,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583235135,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1227",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_delay_queue",
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234976,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583413634,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1362",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_delay_queue",
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583413472,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583621531,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1421",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621456,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583726133,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1545",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583726064,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583914661,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1543",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583914592,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584017877,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1559",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017808,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584412613,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1625",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584412656,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584527221,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1716",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584528176,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584559013,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1735",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584559056,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584970485,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1746",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584970528,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585678299,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:2260",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585673024,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586455195,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:2403",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586449216,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586699067,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:2365",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtio_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586695616,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586970315,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:2384",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtio_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586966976,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495848680,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1559",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495848752,
      "name": "blk_mq_stop_hw_queue",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229196972,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1559",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229196876,
      "name": "blk_mq_stop_hw_queue",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290043612,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1559",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290043424,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274977754,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1559",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274977664,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583986613,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1559",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986544,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583922469,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1559",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922400,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583970373,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1559",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583970304,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_stop_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584072501,
      "name": "blk_mq_stop_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1559",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_stop_hw_queues"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584072432,
      "name": "blk_mq_stop_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
