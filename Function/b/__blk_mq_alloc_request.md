# Function: <code>__blk_mq_alloc_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct request * __blk_mq_alloc_request(struct blk_mq_alloc_data * data, int rw)
```

```json
{
  "name": "__blk_mq_alloc_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582789072,
      "name": "__blk_mq_alloc_request",
      "external": false,
      "loc": "block/blk-mq.c:210",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_map_request",
        "block/blk-mq.c:blk_mq_map_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582789072,
      "name": "__blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
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
struct request * __blk_mq_alloc_request(struct blk_mq_alloc_data * data, int op, int op_flags)
```

```json
{
  "name": "__blk_mq_alloc_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583066560,
      "name": "__blk_mq_alloc_request",
      "external": false,
      "loc": "block/blk-mq.c:211",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_request",
        "block/blk-mq.c:blk_mq_map_request",
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583066560,
      "name": "__blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
struct request * __blk_mq_alloc_request(struct blk_mq_alloc_data * data, unsigned int op)
```

```json
{
  "name": "__blk_mq_alloc_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583174096,
      "name": "__blk_mq_alloc_request",
      "external": false,
      "loc": "block/blk-mq.c:218",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583174096,
      "name": "__blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
    }
  ]
}
```
</details>
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
struct request * __blk_mq_alloc_request(struct blk_mq_alloc_data * data)
```

```json
{
  "name": "__blk_mq_alloc_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584410720,
      "name": "__blk_mq_alloc_request",
      "external": false,
      "loc": "block/blk-mq.c:350",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584410720,
      "name": "__blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
struct request * __blk_mq_alloc_request(struct blk_mq_alloc_data * data)
```

```json
{
  "name": "__blk_mq_alloc_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584527264,
      "name": "__blk_mq_alloc_request",
      "external": false,
      "loc": "block/blk-mq.c:348",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584527264,
      "name": "__blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
struct request * __blk_mq_alloc_request(struct blk_mq_alloc_data * data)
```

```json
{
  "name": "__blk_mq_alloc_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584559104,
      "name": "__blk_mq_alloc_request",
      "external": false,
      "loc": "block/blk-mq.c:348",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584559104,
      "name": "__blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
struct request * __blk_mq_alloc_request(struct blk_mq_alloc_data * data)
```

```json
{
  "name": "__blk_mq_alloc_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584970576,
      "name": "__blk_mq_alloc_request",
      "external": false,
      "loc": "block/blk-mq.c:355",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584970576,
      "name": "__blk_mq_alloc_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    }
  ]
}
```
</details>
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
<code>int rw</code>
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
<b>Param type changed. </b>
<code>int op</code> ➡️ <code>unsigned int op</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct request * __blk_mq_alloc_request(struct blk_mq_alloc_data * data, unsigned int op)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct request * __blk_mq_alloc_request(struct blk_mq_alloc_data * data)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct request * __blk_mq_alloc_request(struct blk_mq_alloc_data * data)
```
</details>
</li>
</ul>
