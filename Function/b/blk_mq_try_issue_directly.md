# Function: <code>blk_mq_try_issue_directly</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void blk_mq_try_issue_directly(struct request * rq, blk_qc_t * cookie)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583190240,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1299",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583190240,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583240752,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1536",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583240752,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583419424,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1673",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583419424,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583630464,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1719",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583630464,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
blk_status_t blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie, bool bypass, bool last)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583737488,
      "name": "blk_mq_try_issue_directly",
      "external": true,
      "loc": "block/blk-mq.c:1808",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583737488,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583925056,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1854",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583925056,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584028400,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1874",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584028400,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584419248,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1934",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584419248,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584535648,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:2031",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584535648,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584568160,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:2055",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584568160,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584982656,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:2066",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584982656,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585694096,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:2531",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585694096,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586473424,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:2674",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586473424,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586724256,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:2632",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586724256,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586995472,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:2654",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_submit_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586995472,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
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
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495861112,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1874",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495861112,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229207988,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1874",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229207988,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290059152,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1874",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290059152,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274987636,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1874",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274987636,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583997136,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1874",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583997136,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583932976,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1874",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932976,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583980896,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1874",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583980896,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void blk_mq_try_issue_directly(struct blk_mq_hw_ctx * hctx, struct request * rq, blk_qc_t * cookie)
```

```json
{
  "name": "blk_mq_try_issue_directly",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584083184,
      "name": "blk_mq_try_issue_directly",
      "external": false,
      "loc": "block/blk-mq.c:1874",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584083184,
      "name": "blk_mq_try_issue_directly",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void blk_mq_try_issue_directly(struct request * rq, blk_qc_t * cookie)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_mq_hw_ctx * hctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>rq, cookie</code> ➡️ <code>hctx, rq, cookie</code>
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
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool bypass</code>
</li>
<li>
<b>Param added. </b>
<code>bool last</code>
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
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool bypass</code>
</li>
<li>
<b>Param removed. </b>
<code>bool last</code>
</li>
<li>
<b>Return type changed. </b>
<code>blk_status_t</code> ➡️ <code>void</code>
</li>
</ul>
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
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
