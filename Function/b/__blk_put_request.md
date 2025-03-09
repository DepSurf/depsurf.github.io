# Function: <code>__blk_put_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __blk_put_request(struct request_queue * q, struct request * req)
```

```json
{
  "name": "__blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582737872,
      "name": "__blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:1463",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_put_request",
        "block/blk-core.c:blk_finish_request",
        "block/blk-core.c:blk_finish_request",
        "block/blk-merge.c:attempt_merge",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/md/dm.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582737872,
      "name": "__blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void __blk_put_request(struct request_queue * q, struct request * req)
```

```json
{
  "name": "__blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583020064,
      "name": "__blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:1422",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_finish_request",
        "block/blk-core.c:blk_finish_request",
        "block/blk-core.c:blk_put_request",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583020064,
      "name": "__blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
void __blk_put_request(struct request_queue * q, struct request * req)
```

```json
{
  "name": "__blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583125200,
      "name": "__blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:1424",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_finish_request",
        "block/blk-core.c:blk_finish_request",
        "block/blk-core.c:blk_put_request",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/md/dm-rq.c:end_clone_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583125200,
      "name": "__blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
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
void __blk_put_request(struct request_queue * q, struct request * req)
```

```json
{
  "name": "__blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583184000,
      "name": "__blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:1525",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_finish_request",
        "block/blk-core.c:blk_finish_request",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_put_request",
        "block/blk-merge.c:blk_attempt_req_merge",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/sg.c:sg_rq_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583184000,
      "name": "__blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
void __blk_put_request(struct request_queue * q, struct request * req)
```

```json
{
  "name": "__blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583362592,
      "name": "__blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:1644",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_finish_request",
        "block/blk-core.c:blk_finish_request",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_put_request",
        "block/blk-merge.c:blk_attempt_req_merge",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/sg.c:sg_rq_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583362592,
      "name": "__blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
void __blk_put_request(struct request_queue * q, struct request * req)
```

```json
{
  "name": "__blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583570368,
      "name": "__blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:1740",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_finish_request",
        "block/blk-core.c:blk_finish_request",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_put_request",
        "block/blk-merge.c:blk_attempt_req_merge",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/sg.c:sg_rq_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583570368,
      "name": "__blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
void __blk_put_request(struct request_queue * q, struct request * req)
```
</details>
</li>
</ul>
