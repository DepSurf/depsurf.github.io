# Function: <code>blk_run_queue_async</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_run_queue_async(struct request_queue * q)
```

```json
{
  "name": "blk_run_queue_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582733968,
      "name": "blk_run_queue_async",
      "external": true,
      "loc": "block/blk-core.c:354",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_start_queue_async",
        "block/blk-core.c:queue_unplugged",
        "block/blk-flush.c:flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "drivers/md/dm.c:rq_completed",
        "drivers/md/dm.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582733968,
      "name": "blk_run_queue_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void blk_run_queue_async(struct request_queue * q)
```

```json
{
  "name": "blk_run_queue_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583016208,
      "name": "blk_run_queue_async",
      "external": true,
      "loc": "block/blk-core.c:354",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:queue_unplugged",
        "block/blk-core.c:blk_start_queue_async",
        "block/blk-flush.c:flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "drivers/md/dm-rq.c:dm_requeue_original_request",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583016208,
      "name": "blk_run_queue_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void blk_run_queue_async(struct request_queue * q)
```

```json
{
  "name": "blk_run_queue_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583121040,
      "name": "blk_run_queue_async",
      "external": true,
      "loc": "block/blk-core.c:355",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:queue_unplugged",
        "block/blk-core.c:blk_start_queue_async",
        "block/blk-flush.c:flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "drivers/md/dm-rq.c:dm_requeue_original_request",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583121040,
      "name": "blk_run_queue_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void blk_run_queue_async(struct request_queue * q)
```

```json
{
  "name": "blk_run_queue_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583176912,
      "name": "blk_run_queue_async",
      "external": true,
      "loc": "block/blk-core.c:413",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:queue_unplugged",
        "block/blk-core.c:blk_start_queue_async",
        "block/blk-flush.c:flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "drivers/md/dm-rq.c:dm_requeue_original_request",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583176912,
      "name": "blk_run_queue_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void blk_run_queue_async(struct request_queue * q)
```

```json
{
  "name": "blk_run_queue_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583351840,
      "name": "blk_run_queue_async",
      "external": true,
      "loc": "block/blk-core.c:446",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:queue_unplugged",
        "block/blk-core.c:blk_start_queue_async",
        "block/blk-flush.c:flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583351840,
      "name": "blk_run_queue_async",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void blk_run_queue_async(struct request_queue * q)
```

```json
{
  "name": "blk_run_queue_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583561408,
      "name": "blk_run_queue_async",
      "external": true,
      "loc": "block/blk-core.c:507",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:queue_unplugged",
        "block/blk-core.c:blk_start_queue_async",
        "block/blk-flush.c:flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583561408,
      "name": "blk_run_queue_async",
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
void blk_run_queue_async(struct request_queue * q)
```
</details>
</li>
</ul>
