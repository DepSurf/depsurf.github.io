# Function: <code>blk_mq_get_request</code>

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
struct request * blk_mq_get_request(struct request_queue * q, struct bio * bio, unsigned int op, struct blk_mq_alloc_data * data)
```

```json
{
  "name": "blk_mq_get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583232208,
      "name": "blk_mq_get_request",
      "external": false,
      "loc": "block/blk-mq.c:297",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583232208,
      "name": "blk_mq_get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
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
struct request * blk_mq_get_request(struct request_queue * q, struct bio * bio, unsigned int op, struct blk_mq_alloc_data * data)
```

```json
{
  "name": "blk_mq_get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583409680,
      "name": "blk_mq_get_request",
      "external": false,
      "loc": "block/blk-mq.c:331",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583409680,
      "name": "blk_mq_get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 925
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
struct request * blk_mq_get_request(struct request_queue * q, struct bio * bio, unsigned int op, struct blk_mq_alloc_data * data)
```

```json
{
  "name": "blk_mq_get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583624048,
      "name": "blk_mq_get_request",
      "external": false,
      "loc": "block/blk-mq.c:339",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583624048,
      "name": "blk_mq_get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 969
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
struct request * blk_mq_get_request(struct request_queue * q, struct bio * bio, struct blk_mq_alloc_data * data)
```

```json
{
  "name": "blk_mq_get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583729024,
      "name": "blk_mq_get_request",
      "external": false,
      "loc": "block/blk-mq.c:350",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583729024,
      "name": "blk_mq_get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1083
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
struct request * blk_mq_get_request(struct request_queue * q, struct bio * bio, struct blk_mq_alloc_data * data)
```

```json
{
  "name": "blk_mq_get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583915968,
      "name": "blk_mq_get_request",
      "external": false,
      "loc": "block/blk-mq.c:351",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583915968,
      "name": "blk_mq_get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 987
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
struct request * blk_mq_get_request(struct request_queue * q, struct bio * bio, struct blk_mq_alloc_data * data)
```

```json
{
  "name": "blk_mq_get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584019184,
      "name": "blk_mq_get_request",
      "external": false,
      "loc": "block/blk-mq.c:356",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584019184,
      "name": "blk_mq_get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1041
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct request * blk_mq_get_request(struct request_queue * q, struct bio * bio, struct blk_mq_alloc_data * data)
```

```json
{
  "name": "blk_mq_get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495855512,
      "name": "blk_mq_get_request",
      "external": false,
      "loc": "block/blk-mq.c:356",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495855512,
      "name": "blk_mq_get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 940
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
struct request * blk_mq_get_request(struct request_queue * q, struct bio * bio, struct blk_mq_alloc_data * data)
```

```json
{
  "name": "blk_mq_get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229198428,
      "name": "blk_mq_get_request",
      "external": false,
      "loc": "block/blk-mq.c:356",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229198428,
      "name": "blk_mq_get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1004
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
struct request * blk_mq_get_request(struct request_queue * q, struct bio * bio, struct blk_mq_alloc_data * data)
```

```json
{
  "name": "blk_mq_get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290045840,
      "name": "blk_mq_get_request",
      "external": false,
      "loc": "block/blk-mq.c:356",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290045840,
      "name": "blk_mq_get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1244
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
struct request * blk_mq_get_request(struct request_queue * q, struct bio * bio, struct blk_mq_alloc_data * data)
```

```json
{
  "name": "blk_mq_get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274979000,
      "name": "blk_mq_get_request",
      "external": false,
      "loc": "block/blk-mq.c:356",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274979000,
      "name": "blk_mq_get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 806
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
struct request * blk_mq_get_request(struct request_queue * q, struct bio * bio, struct blk_mq_alloc_data * data)
```

```json
{
  "name": "blk_mq_get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583987920,
      "name": "blk_mq_get_request",
      "external": false,
      "loc": "block/blk-mq.c:356",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583987920,
      "name": "blk_mq_get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1041
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
struct request * blk_mq_get_request(struct request_queue * q, struct bio * bio, struct blk_mq_alloc_data * data)
```

```json
{
  "name": "blk_mq_get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583923776,
      "name": "blk_mq_get_request",
      "external": false,
      "loc": "block/blk-mq.c:356",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583923776,
      "name": "blk_mq_get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1041
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
struct request * blk_mq_get_request(struct request_queue * q, struct bio * bio, struct blk_mq_alloc_data * data)
```

```json
{
  "name": "blk_mq_get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583971680,
      "name": "blk_mq_get_request",
      "external": false,
      "loc": "block/blk-mq.c:356",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583971680,
      "name": "blk_mq_get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1041
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
struct request * blk_mq_get_request(struct request_queue * q, struct bio * bio, struct blk_mq_alloc_data * data)
```

```json
{
  "name": "blk_mq_get_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584075440,
      "name": "blk_mq_get_request",
      "external": false,
      "loc": "block/blk-mq.c:356",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584075440,
      "name": "blk_mq_get_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1071
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
struct request * blk_mq_get_request(struct request_queue * q, struct bio * bio, unsigned int op, struct blk_mq_alloc_data * data)
```
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
<b>Param removed. </b>
<code>unsigned int op</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, bio, op, data</code> ➡️ <code>q, bio, data</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct request * blk_mq_get_request(struct request_queue * q, struct bio * bio, struct blk_mq_alloc_data * data)
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
