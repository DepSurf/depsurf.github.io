# Function: <code>blk_requeue_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_requeue_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "blk_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582736144,
      "name": "blk_requeue_request",
      "external": true,
      "loc": "block/blk-core.c:1385",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-tag.c:blk_queue_invalidate_tags",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/md/dm.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582736144,
      "name": "blk_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void blk_requeue_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "blk_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583018336,
      "name": "blk_requeue_request",
      "external": true,
      "loc": "block/blk-core.c:1344",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-tag.c:blk_queue_invalidate_tags",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583018336,
      "name": "blk_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void blk_requeue_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "blk_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583123104,
      "name": "blk_requeue_request",
      "external": true,
      "loc": "block/blk-core.c:1345",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-tag.c:blk_queue_invalidate_tags",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583123104,
      "name": "blk_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void blk_requeue_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "blk_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583178192,
      "name": "blk_requeue_request",
      "external": true,
      "loc": "block/blk-core.c:1446",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-tag.c:blk_queue_invalidate_tags",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583178192,
      "name": "blk_requeue_request",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void blk_requeue_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "blk_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583353088,
      "name": "blk_requeue_request",
      "external": true,
      "loc": "block/blk-core.c:1551",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-tag.c:blk_queue_invalidate_tags",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353088,
      "name": "blk_requeue_request",
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
void blk_requeue_request(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "blk_requeue_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583562768,
      "name": "blk_requeue_request",
      "external": true,
      "loc": "block/blk-core.c:1647",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583562768,
      "name": "blk_requeue_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void blk_requeue_request(struct request_queue * q, struct request * rq)
```
</details>
</li>
</ul>
