# Function: <code>blk_try_enter_queue</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool blk_try_enter_queue(struct request_queue * q, bool pm)
```

```json
{
  "name": "blk_try_enter_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584925120,
      "name": "blk_try_enter_queue",
      "external": false,
      "loc": "block/blk-core.c:411",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:blk_queue_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584925120,
      "name": "blk_try_enter_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_try_enter_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585636127,
      "name": "blk_try_enter_queue",
      "external": false,
      "loc": "block/blk.h:51",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:bio_poll",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585677673,
      "name": "blk_try_enter_queue",
      "external": false,
      "loc": "block/blk.h:51",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_new_requests"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_try_enter_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586407364,
      "name": "blk_try_enter_queue",
      "external": false,
      "loc": "block/blk.h:41",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:bio_poll",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586453833,
      "name": "blk_try_enter_queue",
      "external": false,
      "loc": "block/blk.h:41",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_new_requests"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_try_enter_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586649395,
      "name": "blk_try_enter_queue",
      "external": false,
      "loc": "block/blk.h:41",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586717286,
      "name": "blk_try_enter_queue",
      "external": false,
      "loc": "block/blk.h:41",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_new_requests"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_try_enter_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586920563,
      "name": "blk_try_enter_queue",
      "external": false,
      "loc": "block/blk.h:40",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586997766,
      "name": "blk_try_enter_queue",
      "external": false,
      "loc": "block/blk.h:40",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_submit_bio"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool blk_try_enter_queue(struct request_queue * q, bool pm)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool blk_try_enter_queue(struct request_queue * q, bool pm)
```
</details>
</li>
</ul>
