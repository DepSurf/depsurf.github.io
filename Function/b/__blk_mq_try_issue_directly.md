# Function: <code>__blk_mq_try_issue_directly</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool may_sleep)
```

```json
{
  "name": "__blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583240448,
      "name": "__blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1486",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583240448,
      "name": "__blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
void __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool may_sleep)
```

```json
{
  "name": "__blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583418992,
      "name": "__blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1618",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583418992,
      "name": "__blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool bypass_insert)
```

```json
{
  "name": "__blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583630096,
      "name": "__blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1678",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583630096,
      "name": "__blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool bypass_insert, bool last)
```

```json
{
  "name": "__blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583924608,
      "name": "__blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1813",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583924608,
      "name": "__blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool bypass_insert, bool last)
```

```json
{
  "name": "__blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584027952,
      "name": "__blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1833",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584027952,
      "name": "__blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool bypass_insert, bool last)
```

```json
{
  "name": "__blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584414960,
      "name": "__blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1881",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584414960,
      "name": "__blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool bypass_insert, bool last)
```

```json
{
  "name": "__blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584531248,
      "name": "__blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1978",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584531248,
      "name": "__blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool bypass_insert, bool last)
```

```json
{
  "name": "__blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584561776,
      "name": "__blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1998",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584561776,
      "name": "__blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
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
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool bypass_insert, bool last)
```

```json
{
  "name": "__blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584982160,
      "name": "__blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:2009",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584982160,
      "name": "__blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
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
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, bool bypass_insert, bool last)
```

```json
{
  "name": "__blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585693104,
      "name": "__blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:2476",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585693104,
      "name": "__blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, bool bypass_insert, bool last)
```

```json
{
  "name": "__blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586472320,
      "name": "__blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:2619",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586472320,
      "name": "__blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool bypass_insert, bool last)
```

```json
{
  "name": "__blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495860664,
      "name": "__blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1833",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495860664,
      "name": "__blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool bypass_insert, bool last)
```

```json
{
  "name": "__blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229207508,
      "name": "__blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1833",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229207508,
      "name": "__blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool bypass_insert, bool last)
```

```json
{
  "name": "__blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290058448,
      "name": "__blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1833",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290058448,
      "name": "__blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
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
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool bypass_insert, bool last)
```

```json
{
  "name": "__blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274987302,
      "name": "__blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1833",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274987302,
      "name": "__blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool bypass_insert, bool last)
```

```json
{
  "name": "__blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583996688,
      "name": "__blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1833",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583996688,
      "name": "__blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool bypass_insert, bool last)
```

```json
{
  "name": "__blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583932528,
      "name": "__blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1833",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932528,
      "name": "__blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool bypass_insert, bool last)
```

```json
{
  "name": "__blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583980448,
      "name": "__blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1833",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583980448,
      "name": "__blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool bypass_insert, bool last)
```

```json
{
  "name": "__blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584082736,
      "name": "__blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1833",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584082736,
      "name": "__blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool may_sleep)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool bypass_insert</code>
</li>
<li>
<b>Param removed. </b>
<code>bool may_sleep</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>blk_status_t</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool bypass_insert)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool bypass_insert, bool last)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>blk_qc_t * cookie</code>
</li>
<li>
<b>Param reordered. </b>
<code>hctx, rq, cookie, bypass_insert, last</code> ➡️ <code>hctx, rq, bypass_insert, last</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, bool bypass_insert, bool last)
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
