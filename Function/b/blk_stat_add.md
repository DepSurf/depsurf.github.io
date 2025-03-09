# Function: <code>blk_stat_add</code>

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
void blk_stat_add(struct blk_rq_stat * stat, struct request * rq)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583198144,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:195",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_finish_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583198144,
      "name": "blk_stat_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
void blk_stat_add(struct request * rq)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583253920,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:81",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_finish_request",
        "block/blk-mq.c:__blk_mq_complete_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583253920,
      "name": "blk_stat_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void blk_stat_add(struct request * rq)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583433248,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:50",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_finish_request",
        "block/blk-mq.c:__blk_mq_complete_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583433248,
      "name": "blk_stat_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583644416,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:50",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_finish_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583644416,
      "name": "blk_stat_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583750656,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:50",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583750656,
      "name": "blk_stat_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583939728,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:51",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583939728,
      "name": "blk_stat_add",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584043200,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:51",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584043200,
      "name": "blk_stat_add",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584438960,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:51",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584438960,
      "name": "blk_stat_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584555776,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:51",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584555776,
      "name": "blk_stat_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584588576,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:51",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584588576,
      "name": "blk_stat_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585003136,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:51",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585003136,
      "name": "blk_stat_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585717648,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:51",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_end_request_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585717648,
      "name": "blk_stat_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586498176,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:51",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_end_request_batch",
        "block/blk-mq.c:__blk_mq_end_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586498176,
      "name": "blk_stat_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586745792,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:50",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_end_request_batch",
        "block/blk-mq.c:blk_mq_end_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586745792,
      "name": "blk_stat_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587017952,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:50",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_end_request_batch",
        "block/blk-mq.c:blk_mq_end_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587017952,
      "name": "blk_stat_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495878400,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:51",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495878400,
      "name": "blk_stat_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229223972,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:51",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229223972,
      "name": "blk_stat_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290080240,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:51",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290080240,
      "name": "blk_stat_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275001000,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:51",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275001000,
      "name": "blk_stat_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584011936,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:51",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584011936,
      "name": "blk_stat_add",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583947760,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:51",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583947760,
      "name": "blk_stat_add",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583995696,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:51",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583995696,
      "name": "blk_stat_add",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void blk_stat_add(struct request * rq, u64 now)
```

```json
{
  "name": "blk_stat_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584098016,
      "name": "blk_stat_add",
      "external": true,
      "loc": "block/blk-stat.c:51",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584098016,
      "name": "blk_stat_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void blk_stat_add(struct blk_rq_stat * stat, struct request * rq)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct blk_rq_stat * stat</code>
</li>
<li>
<b>Param reordered. </b>
<code>stat, rq</code> ➡️ <code>rq</code>
</li>
</ul>
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
<code>u64 now</code>
</li>
</ul>
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
