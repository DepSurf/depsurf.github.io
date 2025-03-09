# Function: <code>wbt_requeue</code>

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
void wbt_requeue(struct rq_wb * rwb, struct blk_issue_stat * stat)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583345728,
      "name": "wbt_requeue",
      "external": true,
      "loc": "block/blk-wbt.c:645",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583345728,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void wbt_requeue(struct rq_wb * rwb, struct blk_issue_stat * stat)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583403712,
      "name": "wbt_requeue",
      "external": true,
      "loc": "block/blk-wbt.c:632",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_requeue_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583403712,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void wbt_requeue(struct rq_wb * rwb, struct blk_issue_stat * stat)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583583264,
      "name": "wbt_requeue",
      "external": true,
      "loc": "block/blk-wbt.c:631",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_requeue_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583583264,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void wbt_requeue(struct rq_wb * rwb, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583800032,
      "name": "wbt_requeue",
      "external": true,
      "loc": "block/blk-wbt.c:664",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_requeue_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583800032,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbt_requeue(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583880048,
      "name": "wbt_requeue",
      "external": false,
      "loc": "block/blk-wbt.c:620",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583880048,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbt_requeue(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584070656,
      "name": "wbt_requeue",
      "external": false,
      "loc": "block/blk-wbt.c:621",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584070656,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbt_requeue(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584193312,
      "name": "wbt_requeue",
      "external": false,
      "loc": "block/blk-wbt.c:623",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584193312,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbt_requeue(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584587312,
      "name": "wbt_requeue",
      "external": false,
      "loc": "block/blk-wbt.c:615",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584587312,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbt_requeue(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584705856,
      "name": "wbt_requeue",
      "external": false,
      "loc": "block/blk-wbt.c:615",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584705856,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbt_requeue(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584734480,
      "name": "wbt_requeue",
      "external": false,
      "loc": "block/blk-wbt.c:616",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584734480,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbt_requeue(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585162224,
      "name": "wbt_requeue",
      "external": false,
      "loc": "block/blk-wbt.c:618",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585162224,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void wbt_requeue(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585898752,
      "name": "wbt_requeue",
      "external": false,
      "loc": "block/blk-wbt.c:618",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585898752,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void wbt_requeue(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586686544,
      "name": "wbt_requeue",
      "external": false,
      "loc": "block/blk-wbt.c:632",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586686544,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbt_requeue(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586948144,
      "name": "wbt_requeue",
      "external": false,
      "loc": "block/blk-wbt.c:691",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586948144,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbt_requeue(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587228576,
      "name": "wbt_requeue",
      "external": false,
      "loc": "block/blk-wbt.c:690",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587228576,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void wbt_requeue(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496058344,
      "name": "wbt_requeue",
      "external": false,
      "loc": "block/blk-wbt.c:623",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496058344,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void wbt_requeue(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229388984,
      "name": "wbt_requeue",
      "external": false,
      "loc": "block/blk-wbt.c:623",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229388984,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void wbt_requeue(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290295968,
      "name": "wbt_requeue",
      "external": false,
      "loc": "block/blk-wbt.c:623",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290295968,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void wbt_requeue(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275135190,
      "name": "wbt_requeue",
      "external": false,
      "loc": "block/blk-wbt.c:623",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275135190,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void wbt_requeue(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584162048,
      "name": "wbt_requeue",
      "external": false,
      "loc": "block/blk-wbt.c:623",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584162048,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void wbt_requeue(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584097312,
      "name": "wbt_requeue",
      "external": false,
      "loc": "block/blk-wbt.c:623",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584097312,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void wbt_requeue(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584145808,
      "name": "wbt_requeue",
      "external": false,
      "loc": "block/blk-wbt.c:623",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584145808,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void wbt_requeue(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_requeue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584249776,
      "name": "wbt_requeue",
      "external": false,
      "loc": "block/blk-wbt.c:623",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584249776,
      "name": "wbt_requeue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void wbt_requeue(struct rq_wb * rwb, struct blk_issue_stat * stat)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<code>struct request * rq</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blk_issue_stat * stat</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rq_qos * rqos</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rq_wb * rwb</code>
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
