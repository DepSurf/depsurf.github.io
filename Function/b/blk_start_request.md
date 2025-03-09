# Function: <code>blk_start_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_start_request(struct request * req)
```

```json
{
  "name": "blk_start_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582756848,
      "name": "blk_start_request",
      "external": true,
      "loc": "block/blk-core.c:2502",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_peek_request",
        "block/blk-core.c:blk_fetch_request",
        "block/blk-tag.c:blk_queue_start_tag",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/md/dm.c:dm_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582756848,
      "name": "blk_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void blk_start_request(struct request * req)
```

```json
{
  "name": "blk_start_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583034800,
      "name": "blk_start_request",
      "external": true,
      "loc": "block/blk-core.c:2474",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_fetch_request",
        "block/blk-core.c:blk_peek_request",
        "block/blk-tag.c:blk_queue_start_tag",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/md/dm-rq.c:dm_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583034800,
      "name": "blk_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void blk_start_request(struct request * req)
```

```json
{
  "name": "blk_start_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583139744,
      "name": "blk_start_request",
      "external": true,
      "loc": "block/blk-core.c:2457",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_fetch_request",
        "block/blk-core.c:blk_peek_request",
        "block/blk-tag.c:blk_queue_start_tag",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/md/dm-rq.c:dm_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583139744,
      "name": "blk_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void blk_start_request(struct request * req)
```

```json
{
  "name": "blk_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583197072,
      "name": "blk_start_request",
      "external": true,
      "loc": "block/blk-core.c:2642",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_fetch_request",
        "block/blk-core.c:blk_peek_request",
        "block/blk-tag.c:blk_queue_start_tag",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/md/dm-rq.c:dm_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583197072,
      "name": "blk_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void blk_start_request(struct request * req)
```

```json
{
  "name": "blk_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583353808,
      "name": "blk_start_request",
      "external": true,
      "loc": "block/blk-core.c:2845",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_fetch_request",
        "block/blk-core.c:blk_peek_request",
        "block/blk-tag.c:blk_queue_start_tag",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/md/dm-rq.c:dm_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353808,
      "name": "blk_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void blk_start_request(struct request * req)
```

```json
{
  "name": "blk_start_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583563360,
      "name": "blk_start_request",
      "external": true,
      "loc": "block/blk-core.c:2986",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_fetch_request",
        "block/blk-core.c:blk_peek_request",
        "block/blk-tag.c:blk_queue_start_tag",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/md/dm-rq.c:dm_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583563360,
      "name": "blk_start_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
void blk_start_request(struct request * req)
```
</details>
</li>
</ul>
