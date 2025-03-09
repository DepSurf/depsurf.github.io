# Function: <code>dd_insert_request</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dd_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583858295,
      "name": "dd_insert_request",
      "external": false,
      "loc": "block/mq-deadline.c:491",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_insert_requests"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dd_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584048903,
      "name": "dd_insert_request",
      "external": false,
      "loc": "block/mq-deadline.c:493",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_insert_requests"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dd_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584171319,
      "name": "dd_insert_request",
      "external": false,
      "loc": "block/mq-deadline.c:483",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_insert_requests"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dd_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584568199,
      "name": "dd_insert_request",
      "external": false,
      "loc": "block/mq-deadline.c:483",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_insert_requests"
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
  "name": "dd_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584686532,
      "name": "dd_insert_request",
      "external": false,
      "loc": "block/mq-deadline.c:485",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_insert_requests"
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
  "name": "dd_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584715495,
      "name": "dd_insert_request",
      "external": false,
      "loc": "block/mq-deadline.c:484",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_insert_requests"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void dd_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "dd_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585143072,
      "name": "dd_insert_request",
      "external": false,
      "loc": "block/mq-deadline.c:659",
      "file": "block/mq-deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585143072,
      "name": "dd_insert_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
  "name": "dd_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585874880,
      "name": "dd_insert_request",
      "external": false,
      "loc": "block/mq-deadline.c:712",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585874880,
      "name": "dd_insert_request.isra.0",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dd_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586659776,
      "name": "dd_insert_request",
      "external": false,
      "loc": "block/mq-deadline.c:770",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586659776,
      "name": "dd_insert_request.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dd_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dd_insert_request",
      "external": false,
      "loc": "block/mq-deadline.c:795",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586922384,
      "name": "dd_insert_request.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 971
    },
    {
      "addr": 18446744071596634073,
      "name": "dd_insert_request.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dd_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "dd_insert_request",
      "external": false,
      "loc": "block/mq-deadline.c:795",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:dd_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587200800,
      "name": "dd_insert_request.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1003
    },
    {
      "addr": 18446744071597541177,
      "name": "dd_insert_request.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "dd_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496026372,
      "name": "dd_insert_request",
      "external": false,
      "loc": "block/mq-deadline.c:483",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_insert_requests"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "dd_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229367336,
      "name": "dd_insert_request",
      "external": false,
      "loc": "block/mq-deadline.c:483",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_insert_requests"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "dd_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290259132,
      "name": "dd_insert_request",
      "external": false,
      "loc": "block/mq-deadline.c:483",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_insert_requests"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "dd_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275115636,
      "name": "dd_insert_request",
      "external": false,
      "loc": "block/mq-deadline.c:483",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_insert_requests"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dd_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584140055,
      "name": "dd_insert_request",
      "external": false,
      "loc": "block/mq-deadline.c:483",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_insert_requests"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dd_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584075591,
      "name": "dd_insert_request",
      "external": false,
      "loc": "block/mq-deadline.c:483",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_insert_requests"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dd_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584123815,
      "name": "dd_insert_request",
      "external": false,
      "loc": "block/mq-deadline.c:483",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_insert_requests"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dd_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584228007,
      "name": "dd_insert_request",
      "external": false,
      "loc": "block/mq-deadline.c:483",
      "file": "block/mq-deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/mq-deadline.c:dd_insert_requests"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void dd_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void dd_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```
</details>
</li>
</ul>
