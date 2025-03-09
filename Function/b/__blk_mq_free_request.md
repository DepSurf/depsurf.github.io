# Function: <code>__blk_mq_free_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __blk_mq_free_request(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582789568,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:269",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_request",
        "block/blk-mq.c:blk_sq_make_request",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582789568,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void __blk_mq_free_request(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583067120,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:325",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_sq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_free_hctx_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583067120,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void __blk_mq_free_request(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583174592,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:322",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_sq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_free_hctx_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583174592,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583620080,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:471",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583620080,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583724736,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:484",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583724736,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583912976,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:481",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583912976,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584016112,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:492",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584016112,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584409104,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:494",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584409104,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584524752,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:488",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584524752,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584557312,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:489",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_put_rq_ref",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584557312,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584968496,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:496",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_put_rq_ref",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584968496,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585672000,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:604",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_put_rq_ref",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585672000,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586447808,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:710",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_put_rq_ref",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586447808,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586704048,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:699",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_put_rq_ref",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586704048,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586971728,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:705",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_put_rq_ref",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586971728,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495846272,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:492",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495846272,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229194344,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:492",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229194344,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290040640,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:492",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290040640,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274976000,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:492",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274976000,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583984848,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:492",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583984848,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583920704,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:492",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583920704,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583968608,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:492",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583968608,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void __blk_mq_free_request(struct request * rq)
```

```json
{
  "name": "__blk_mq_free_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584070624,
      "name": "__blk_mq_free_request",
      "external": false,
      "loc": "block/blk-mq.c:492",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584070624,
      "name": "__blk_mq_free_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void __blk_mq_free_request(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct request * rq)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void __blk_mq_free_request(struct request * rq)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
