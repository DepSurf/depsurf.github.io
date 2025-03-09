# Function: <code>blk_mq_alloc_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct request * blk_mq_alloc_request(struct request_queue * q, int rw, unsigned int flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582796400,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:232",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582796400,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
struct request * blk_mq_alloc_request(struct request_queue * q, int rw, unsigned int flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583075344,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:233",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583075344,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
struct request * blk_mq_alloc_request(struct request_queue * q, int rw, unsigned int flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583176224,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:240",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583176224,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
struct request * blk_mq_alloc_request(struct request_queue * q, unsigned int op, unsigned int flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583233120,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:351",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583233120,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
struct request * blk_mq_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583410608,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:387",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583410608,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct request * blk_mq_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583625024,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:399",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583625024,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
struct request * blk_mq_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583730112,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:412",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583730112,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
struct request * blk_mq_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583916960,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:411",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583916960,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct request * blk_mq_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584020240,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:422",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020240,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct request * blk_mq_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584411040,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:405",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584411040,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
struct request * blk_mq_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584527552,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:401",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584527552,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
struct request * blk_mq_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584559392,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:402",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584559392,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
struct request * blk_mq_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584970960,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:409",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584970960,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
struct request * blk_mq_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585677376,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:510",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "drivers/scsi/scsi_lib.c:__scsi_execute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585677376,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
struct request * blk_mq_alloc_request(struct request_queue * q, blk_opf_t opf, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586453168,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:603",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "drivers/scsi/scsi_lib.c:__scsi_execute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586453168,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
struct request * blk_mq_alloc_request(struct request_queue * q, blk_opf_t opf, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586716544,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:577",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "drivers/block/virtio_blk.c:virtblk_report_zones",
        "drivers/scsi/scsi_lib.c:scsi_execute_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586716544,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 626
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
struct request * blk_mq_alloc_request(struct request_queue * q, blk_opf_t opf, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586988128,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:581",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "drivers/block/virtio_blk.c:virtblk_report_zones",
        "drivers/scsi/scsi_lib.c:scsi_execute_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586988128,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 643
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
struct request * blk_mq_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495856456,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:422",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495856456,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
struct request * blk_mq_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229199432,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:422",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229199432,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct request * blk_mq_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290047088,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:422",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290047088,
      "name": "blk_mq_alloc_request",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct request * blk_mq_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274979806,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:422",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274979806,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct request * blk_mq_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583988976,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:422",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request",
        "drivers/nvme/host/core.c:nvme_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583988976,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct request * blk_mq_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583924832,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:422",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request",
        "drivers/nvme/host/core.c:nvme_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583924832,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct request * blk_mq_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583972736,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:422",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972736,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct request * blk_mq_alloc_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_mq_alloc_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584076512,
      "name": "blk_mq_alloc_request",
      "external": true,
      "loc": "block/blk-mq.c:422",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584076512,
      "name": "blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int op</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int flags</code> ➡️ <code>blk_mq_req_flags_t flags</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_opf_t opf</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int op</code>
</li>
</ul>
</details>
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
