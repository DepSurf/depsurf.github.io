# Function: <code>blk_end_request_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_end_request_all(struct request * rq, int error)
```

```json
{
  "name": "blk_end_request_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582755024,
      "name": "blk_end_request_all",
      "external": true,
      "loc": "block/blk-core.c:2838",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_softirq_done",
        "block/bsg-lib.c:bsg_request_fn",
        "drivers/block/xen-blkfront.c:blkif_recover",
        "drivers/md/dm.c:dm_softirq_done",
        "drivers/md/dm.c:dm_softirq_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582755024,
      "name": "blk_end_request_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void blk_end_request_all(struct request * rq, int error)
```

```json
{
  "name": "blk_end_request_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583032928,
      "name": "blk_end_request_all",
      "external": true,
      "loc": "block/blk-core.c:2810",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_request_fn",
        "block/bsg-lib.c:bsg_softirq_done",
        "drivers/md/dm-rq.c:dm_softirq_done",
        "drivers/md/dm-rq.c:dm_softirq_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583032928,
      "name": "blk_end_request_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void blk_end_request_all(struct request * rq, int error)
```

```json
{
  "name": "blk_end_request_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583137856,
      "name": "blk_end_request_all",
      "external": true,
      "loc": "block/blk-core.c:2807",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_request_fn",
        "block/bsg-lib.c:bsg_destroy_job",
        "drivers/md/dm-rq.c:dm_softirq_done",
        "drivers/md/dm-rq.c:dm_softirq_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583137856,
      "name": "blk_end_request_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void blk_end_request_all(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_end_request_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583194544,
      "name": "blk_end_request_all",
      "external": true,
      "loc": "block/blk-core.c:2955",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_request_fn",
        "block/bsg-lib.c:bsg_job_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194544,
      "name": "blk_end_request_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void blk_end_request_all(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_end_request_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583371040,
      "name": "blk_end_request_all",
      "external": true,
      "loc": "block/blk-core.c:3179",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_request_fn",
        "block/bsg-lib.c:bsg_teardown_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583371040,
      "name": "blk_end_request_all",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void blk_end_request_all(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_end_request_all",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583580608,
      "name": "blk_end_request_all",
      "external": true,
      "loc": "block/blk-core.c:3324",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_request_fn",
        "block/bsg-lib.c:bsg_teardown_job"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583580608,
      "name": "blk_end_request_all",
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
<b>Param type changed. </b>
<code>int error</code> ➡️ <code>blk_status_t error</code>
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
void blk_end_request_all(struct request * rq, blk_status_t error)
```
</details>
</li>
</ul>
