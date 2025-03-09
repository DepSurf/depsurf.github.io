# Function: <code>blk_delay_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_delay_queue(struct request_queue * q, long unsigned int msecs)
```

```json
{
  "name": "blk_delay_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582733568,
      "name": "blk_delay_queue",
      "external": true,
      "loc": "block/blk-core.c:201",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_prep_fn",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/md/dm.c:dm_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582733568,
      "name": "blk_delay_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void blk_delay_queue(struct request_queue * q, long unsigned int msecs)
```

```json
{
  "name": "blk_delay_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583015808,
      "name": "blk_delay_queue",
      "external": true,
      "loc": "block/blk-core.c:201",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_prep_fn",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583015808,
      "name": "blk_delay_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void blk_delay_queue(struct request_queue * q, long unsigned int msecs)
```

```json
{
  "name": "blk_delay_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583120640,
      "name": "blk_delay_queue",
      "external": true,
      "loc": "block/blk-core.c:202",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_prep_fn",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583120640,
      "name": "blk_delay_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void blk_delay_queue(struct request_queue * q, long unsigned int msecs)
```

```json
{
  "name": "blk_delay_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583176672,
      "name": "blk_delay_queue",
      "external": true,
      "loc": "block/blk-core.c:241",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_prep_fn",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583176672,
      "name": "blk_delay_queue",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void blk_delay_queue(struct request_queue * q, long unsigned int msecs)
```

```json
{
  "name": "blk_delay_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583351504,
      "name": "blk_delay_queue",
      "external": true,
      "loc": "block/blk-core.c:241",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_prep_fn",
        "drivers/md/dm-rq.c:dm_old_request_fn",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583351504,
      "name": "blk_delay_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void blk_delay_queue(struct request_queue * q, long unsigned int msecs)
```

```json
{
  "name": "blk_delay_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583561168,
      "name": "blk_delay_queue",
      "external": true,
      "loc": "block/blk-core.c:314",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_prep_fn",
        "drivers/md/dm-rq.c:dm_old_request_fn",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583561168,
      "name": "blk_delay_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void blk_delay_queue(struct request_queue * q, long unsigned int msecs)
```
</details>
</li>
</ul>
