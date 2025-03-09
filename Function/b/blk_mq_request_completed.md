# Function: <code>blk_mq_request_completed</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int blk_mq_request_completed(struct request * rq)
```

```json
{
  "name": "blk_mq_request_completed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584014944,
      "name": "blk_mq_request_completed",
      "external": true,
      "loc": "block/blk-mq.c:672",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584014944,
      "name": "blk_mq_request_completed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_request_completed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584434197,
      "name": "blk_mq_request_completed",
      "external": false,
      "loc": "include/linux/blk-mq.h:494",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_request_completed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584550645,
      "name": "blk_mq_request_completed",
      "external": false,
      "loc": "include/linux/blk-mq.h:492",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_request_completed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584582997,
      "name": "blk_mq_request_completed",
      "external": false,
      "loc": "include/linux/blk-mq.h:497",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_request_completed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584997253,
      "name": "blk_mq_request_completed",
      "external": false,
      "loc": "include/linux/blk-mq.h:507",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_request_completed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585709893,
      "name": "blk_mq_request_completed",
      "external": false,
      "loc": "include/linux/blk-mq.h:784",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs"
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
  "name": "blk_mq_request_completed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586490005,
      "name": "blk_mq_request_completed",
      "external": false,
      "loc": "include/linux/blk-mq.h:804",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs"
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
  "name": "blk_mq_request_completed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586737525,
      "name": "blk_mq_request_completed",
      "external": false,
      "loc": "include/linux/blk-mq.h:800",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs"
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
  "name": "blk_mq_request_completed",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586966619,
      "name": "blk_mq_request_completed",
      "external": false,
      "loc": "include/linux/blk-mq.h:791",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_rq_inflight"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587009621,
      "name": "blk_mq_request_completed",
      "external": false,
      "loc": "include/linux/blk-mq.h:791",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int blk_mq_request_completed(struct request * rq)
```

```json
{
  "name": "blk_mq_request_completed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495844888,
      "name": "blk_mq_request_completed",
      "external": true,
      "loc": "block/blk-mq.c:672",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495844888,
      "name": "blk_mq_request_completed",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int blk_mq_request_completed(struct request * rq)
```

```json
{
  "name": "blk_mq_request_completed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229193068,
      "name": "blk_mq_request_completed",
      "external": true,
      "loc": "block/blk-mq.c:672",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229193068,
      "name": "blk_mq_request_completed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int blk_mq_request_completed(struct request * rq)
```

```json
{
  "name": "blk_mq_request_completed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290038560,
      "name": "blk_mq_request_completed",
      "external": true,
      "loc": "block/blk-mq.c:672",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290038560,
      "name": "blk_mq_request_completed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int blk_mq_request_completed(struct request * rq)
```

```json
{
  "name": "blk_mq_request_completed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274974942,
      "name": "blk_mq_request_completed",
      "external": true,
      "loc": "block/blk-mq.c:672",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274974942,
      "name": "blk_mq_request_completed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int blk_mq_request_completed(struct request * rq)
```

```json
{
  "name": "blk_mq_request_completed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583983680,
      "name": "blk_mq_request_completed",
      "external": true,
      "loc": "block/blk-mq.c:672",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs",
        "drivers/nvme/host/core.c:nvme_cancel_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583983680,
      "name": "blk_mq_request_completed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int blk_mq_request_completed(struct request * rq)
```

```json
{
  "name": "blk_mq_request_completed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583919536,
      "name": "blk_mq_request_completed",
      "external": true,
      "loc": "block/blk-mq.c:672",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs",
        "drivers/nvme/host/core.c:nvme_cancel_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583919536,
      "name": "blk_mq_request_completed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int blk_mq_request_completed(struct request * rq)
```

```json
{
  "name": "blk_mq_request_completed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583967440,
      "name": "blk_mq_request_completed",
      "external": true,
      "loc": "block/blk-mq.c:672",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583967440,
      "name": "blk_mq_request_completed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int blk_mq_request_completed(struct request * rq)
```

```json
{
  "name": "blk_mq_request_completed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584069456,
      "name": "blk_mq_request_completed",
      "external": true,
      "loc": "block/blk-mq.c:672",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584069456,
      "name": "blk_mq_request_completed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int blk_mq_request_completed(struct request * rq)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int blk_mq_request_completed(struct request * rq)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
