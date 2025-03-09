# Function: <code>wbt_done</code>

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
void wbt_done(struct rq_wb * rwb, struct blk_issue_stat * stat)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583344496,
      "name": "wbt_done",
      "external": true,
      "loc": "block/blk-wbt.c:168",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_finish_request",
        "block/blk-core.c:__blk_put_request",
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344496,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void wbt_done(struct rq_wb * rwb, struct blk_issue_stat * stat)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583402576,
      "name": "wbt_done",
      "external": true,
      "loc": "block/blk-wbt.c:168",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_finish_request",
        "block/blk-core.c:__blk_put_request",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583402576,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void wbt_done(struct rq_wb * rwb, struct blk_issue_stat * stat)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583582144,
      "name": "wbt_done",
      "external": true,
      "loc": "block/blk-wbt.c:168",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_finish_request",
        "block/blk-core.c:__blk_put_request",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583582144,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void wbt_done(struct rq_wb * rwb, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583798752,
      "name": "wbt_done",
      "external": true,
      "loc": "block/blk-wbt.c:197",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_finish_request",
        "block/blk-core.c:__blk_put_request",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583798752,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void wbt_done(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583879296,
      "name": "wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:184",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583879296,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void wbt_done(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584069872,
      "name": "wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:185",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584069872,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void wbt_done(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584193552,
      "name": "wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:185",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584193552,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void wbt_done(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584587472,
      "name": "wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:185",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584587472,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void wbt_done(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584706016,
      "name": "wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:185",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584706016,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void wbt_done(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584734656,
      "name": "wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:186",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584734656,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void wbt_done(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585162400,
      "name": "wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:186",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585162400,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void wbt_done(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585899840,
      "name": "wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:186",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585899840,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void wbt_done(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586687712,
      "name": "wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:187",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586687712,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void wbt_done(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586948240,
      "name": "wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:245",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586948240,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void wbt_done(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587228672,
      "name": "wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:244",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587228672,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void wbt_done(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496058856,
      "name": "wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:185",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496058856,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void wbt_done(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229388180,
      "name": "wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:185",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229388180,
      "name": "wbt_done",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void wbt_done(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290296464,
      "name": "wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:185",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290296464,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
void wbt_done(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275134450,
      "name": "wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:185",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275134450,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void wbt_done(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584162288,
      "name": "wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:185",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584162288,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void wbt_done(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584097552,
      "name": "wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:185",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584097552,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void wbt_done(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584146048,
      "name": "wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:185",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584146048,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void wbt_done(struct rq_qos * rqos, struct request * rq)
```

```json
{
  "name": "wbt_done",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584250336,
      "name": "wbt_done",
      "external": false,
      "loc": "block/blk-wbt.c:185",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584250336,
      "name": "wbt_done",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void wbt_done(struct rq_wb * rwb, struct blk_issue_stat * stat)
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
