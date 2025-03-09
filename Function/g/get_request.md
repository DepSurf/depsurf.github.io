# Function: <code>get_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct request * get_request(struct request_queue * q, int rw_flags, struct bio * bio, gfp_t gfp_mask)
```

```json
{
  "name": "get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582748064,
      "name": "get_request",
      "external": false,
      "loc": "block/blk-core.c:1232",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_get_request",
        "block/blk-core.c:blk_queue_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582748064,
      "name": "get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1933
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
struct request * get_request(struct request_queue * q, int op, int op_flags, struct bio * bio, gfp_t gfp_mask)
```

```json
{
  "name": "get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583026064,
      "name": "get_request",
      "external": false,
      "loc": "block/blk-core.c:1245",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583026064,
      "name": "get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2053
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
struct request * get_request(struct request_queue * q, unsigned int op, struct bio * bio, gfp_t gfp_mask)
```

```json
{
  "name": "get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583130928,
      "name": "get_request",
      "external": false,
      "loc": "block/blk-core.c:1247",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583130928,
      "name": "get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1990
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
struct request * get_request(struct request_queue * q, unsigned int op, struct bio * bio, gfp_t gfp_mask)
```

```json
{
  "name": "get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583185952,
      "name": "get_request",
      "external": false,
      "loc": "block/blk-core.c:1342",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583185952,
      "name": "get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2001
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
struct request * get_request(struct request_queue * q, unsigned int op, struct bio * bio, blk_mq_req_flags_t flags)
```

```json
{
  "name": "get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583364000,
      "name": "get_request",
      "external": false,
      "loc": "block/blk-core.c:1424",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_get_request_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583364000,
      "name": "get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2037
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
struct request * get_request(struct request_queue * q, unsigned int op, struct bio * bio, blk_mq_req_flags_t flags, gfp_t gfp)
```

```json
{
  "name": "get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_request",
      "external": false,
      "loc": "block/blk-core.c:1529",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583571344,
      "name": "get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1992
    },
    {
      "addr": 18446744071583586056,
      "name": "get_request.cold.99",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int op</code>
</li>
<li>
<b>Param added. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, rw_flags, bio, gfp_mask</code> ➡️ <code>q, op, op_flags, bio, gfp_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, op, op_flags, bio, gfp_mask</code> ➡️ <code>q, op, bio, gfp_mask</code>
</li>
<li>
<b>Param type changed. </b>
<code>int op</code> ➡️ <code>unsigned int op</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_mq_req_flags_t flags</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
struct request * get_request(struct request_queue * q, unsigned int op, struct bio * bio, blk_mq_req_flags_t flags, gfp_t gfp)
```
</details>
</li>
</ul>
