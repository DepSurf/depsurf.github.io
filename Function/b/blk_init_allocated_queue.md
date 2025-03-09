# Function: <code>blk_init_allocated_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct request_queue * blk_init_allocated_queue(struct request_queue * q, request_fn_proc * rfn, spinlock_t * lock)
```

```json
{
  "name": "blk_init_allocated_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582750752,
      "name": "blk_init_allocated_queue",
      "external": true,
      "loc": "block/blk-core.c:831",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_queue_node",
        "drivers/md/dm.c:dm_setup_md_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582750752,
      "name": "blk_init_allocated_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
struct request_queue * blk_init_allocated_queue(struct request_queue * q, request_fn_proc * rfn, spinlock_t * lock)
```

```json
{
  "name": "blk_init_allocated_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583028704,
      "name": "blk_init_allocated_queue",
      "external": true,
      "loc": "block/blk-core.c:840",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_queue_node",
        "drivers/md/dm-rq.c:dm_old_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583028704,
      "name": "blk_init_allocated_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
struct request_queue * blk_init_allocated_queue(struct request_queue * q, request_fn_proc * rfn, spinlock_t * lock)
```

```json
{
  "name": "blk_init_allocated_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583133488,
      "name": "blk_init_allocated_queue",
      "external": true,
      "loc": "block/blk-core.c:841",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_queue_node",
        "drivers/md/dm-rq.c:dm_old_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583133488,
      "name": "blk_init_allocated_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int blk_init_allocated_queue(struct request_queue * q)
```

```json
{
  "name": "blk_init_allocated_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583190032,
      "name": "blk_init_allocated_queue",
      "external": true,
      "loc": "block/blk-core.c:970",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_queue_node",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/scsi/scsi_lib.c:scsi_alloc_queue",
        "drivers/md/dm-rq.c:dm_old_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583190032,
      "name": "blk_init_allocated_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int blk_init_allocated_queue(struct request_queue * q)
```

```json
{
  "name": "blk_init_allocated_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583355408,
      "name": "blk_init_allocated_queue",
      "external": true,
      "loc": "block/blk-core.c:1048",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_queue_node",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/scsi/scsi_lib.c:scsi_old_alloc_queue",
        "drivers/md/dm-rq.c:dm_old_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583355408,
      "name": "blk_init_allocated_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int blk_init_allocated_queue(struct request_queue * q)
```

```json
{
  "name": "blk_init_allocated_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583564944,
      "name": "blk_init_allocated_queue",
      "external": true,
      "loc": "block/blk-core.c:1160",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_queue_node",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/scsi/scsi_lib.c:scsi_old_alloc_queue",
        "drivers/md/dm-rq.c:dm_old_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583564944,
      "name": "blk_init_allocated_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>request_fn_proc * rfn</code>
</li>
<li>
<b>Param removed. </b>
<code>spinlock_t * lock</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct request_queue *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
int blk_init_allocated_queue(struct request_queue * q)
```
</details>
</li>
</ul>
