# Function: <code>blk_peek_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct request * blk_peek_request(struct request_queue * q)
```

```json
{
  "name": "blk_peek_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582757248,
      "name": "blk_peek_request",
      "external": true,
      "loc": "block/blk-core.c:2379",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_fetch_request",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/md/dm.c:dm_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582757248,
      "name": "blk_peek_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 642
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
struct request * blk_peek_request(struct request_queue * q)
```

```json
{
  "name": "blk_peek_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583035216,
      "name": "blk_peek_request",
      "external": true,
      "loc": "block/blk-core.c:2349",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_fetch_request",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583035216,
      "name": "blk_peek_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
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
struct request * blk_peek_request(struct request_queue * q)
```

```json
{
  "name": "blk_peek_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583140224,
      "name": "blk_peek_request",
      "external": true,
      "loc": "block/blk-core.c:2332",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_fetch_request",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583140224,
      "name": "blk_peek_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
struct request * blk_peek_request(struct request_queue * q)
```

```json
{
  "name": "blk_peek_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583197280,
      "name": "blk_peek_request",
      "external": true,
      "loc": "block/blk-core.c:2518",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_fetch_request",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583197280,
      "name": "blk_peek_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
struct request * blk_peek_request(struct request_queue * q)
```

```json
{
  "name": "blk_peek_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583371424,
      "name": "blk_peek_request",
      "external": true,
      "loc": "block/blk-core.c:2729",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_fetch_request",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583371424,
      "name": "blk_peek_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct request * blk_peek_request(struct request_queue * q)
```

```json
{
  "name": "blk_peek_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_peek_request",
      "external": true,
      "loc": "block/blk-core.c:2872",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_fetch_request",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583586263,
      "name": "blk_peek_request.cold.102",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583580944,
      "name": "blk_peek_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 689
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
struct request * blk_peek_request(struct request_queue * q)
```
</details>
</li>
</ul>
