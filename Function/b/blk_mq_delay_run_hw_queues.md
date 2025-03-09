# Function: <code>blk_mq_delay_run_hw_queues</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void blk_mq_delay_run_hw_queues(struct request_queue * q, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584416192,
      "name": "blk_mq_delay_run_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1582",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584416192,
      "name": "blk_mq_delay_run_hw_queues",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void blk_mq_delay_run_hw_queues(struct request_queue * q, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532112,
      "name": "blk_mq_delay_run_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1673",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532112,
      "name": "blk_mq_delay_run_hw_queues",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void blk_mq_delay_run_hw_queues(struct request_queue * q, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584563360,
      "name": "blk_mq_delay_run_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1683",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584563360,
      "name": "blk_mq_delay_run_hw_queues",
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void blk_mq_delay_run_hw_queues(struct request_queue * q, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584974256,
      "name": "blk_mq_delay_run_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1694",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584974256,
      "name": "blk_mq_delay_run_hw_queues",
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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_mq_delay_run_hw_queues(struct request_queue * q, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585680592,
      "name": "blk_mq_delay_run_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:2200",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585680592,
      "name": "blk_mq_delay_run_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
void blk_mq_delay_run_hw_queues(struct request_queue * q, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586457520,
      "name": "blk_mq_delay_run_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:2363",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586457520,
      "name": "blk_mq_delay_run_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
void blk_mq_delay_run_hw_queues(struct request_queue * q, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586701056,
      "name": "blk_mq_delay_run_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:2325",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586701056,
      "name": "blk_mq_delay_run_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void blk_mq_delay_run_hw_queues(struct request_queue * q, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586973040,
      "name": "blk_mq_delay_run_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:2344",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586973040,
      "name": "blk_mq_delay_run_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void blk_mq_delay_run_hw_queues(struct request_queue * q, long unsigned int msecs)
```
</details>
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
