# Function: <code>bio_attempt_discard_merge</code>

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
bool bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583195824,
      "name": "bio_attempt_discard_merge",
      "external": true,
      "loc": "block/blk-core.c:1628",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583195824,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
bool bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583373056,
      "name": "bio_attempt_discard_merge",
      "external": true,
      "loc": "block/blk-core.c:1748",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583373056,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
bool bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583582576,
      "name": "bio_attempt_discard_merge",
      "external": true,
      "loc": "block/blk-core.c:1845",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583582576,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
bool bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583693056,
      "name": "bio_attempt_discard_merge",
      "external": true,
      "loc": "block/blk-core.c:641",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583693056,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
bool bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583881744,
      "name": "bio_attempt_discard_merge",
      "external": true,
      "loc": "block/blk-core.c:639",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583881744,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
bool bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583984944,
      "name": "bio_attempt_discard_merge",
      "external": true,
      "loc": "block/blk-core.c:645",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583984944,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
bool bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584373504,
      "name": "bio_attempt_discard_merge",
      "external": true,
      "loc": "block/blk-core.c:701",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584373504,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
enum bio_merge_status bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584511760,
      "name": "bio_attempt_discard_merge",
      "external": false,
      "loc": "block/blk-merge.c:983",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584511760,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
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
enum bio_merge_status bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584546208,
      "name": "bio_attempt_discard_merge",
      "external": false,
      "loc": "block/blk-merge.c:986",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584546208,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
enum bio_merge_status bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584957504,
      "name": "bio_attempt_discard_merge",
      "external": false,
      "loc": "block/blk-merge.c:969",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584957504,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
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
enum bio_merge_status bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585661584,
      "name": "bio_attempt_discard_merge",
      "external": false,
      "loc": "block/blk-merge.c:966",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585661584,
      "name": "bio_attempt_discard_merge",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586436704,
      "name": "bio_attempt_discard_merge",
      "external": false,
      "loc": "block/blk-merge.c:1035",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586436704,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
enum bio_merge_status bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586683872,
      "name": "bio_attempt_discard_merge",
      "external": false,
      "loc": "block/blk-merge.c:1031",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586683872,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
enum bio_merge_status bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586955184,
      "name": "bio_attempt_discard_merge",
      "external": false,
      "loc": "block/blk-merge.c:1027",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586955184,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
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
bool bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495810192,
      "name": "bio_attempt_discard_merge",
      "external": true,
      "loc": "block/blk-core.c:645",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495810192,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
bool bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229161708,
      "name": "bio_attempt_discard_merge",
      "external": true,
      "loc": "block/blk-core.c:645",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229161708,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
bool bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289996400,
      "name": "bio_attempt_discard_merge",
      "external": true,
      "loc": "block/blk-core.c:645",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289996400,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
bool bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274947572,
      "name": "bio_attempt_discard_merge",
      "external": true,
      "loc": "block/blk-core.c:645",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274947572,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
bool bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583953680,
      "name": "bio_attempt_discard_merge",
      "external": true,
      "loc": "block/blk-core.c:645",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583953680,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
bool bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583890608,
      "name": "bio_attempt_discard_merge",
      "external": true,
      "loc": "block/blk-core.c:645",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583890608,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
bool bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583937440,
      "name": "bio_attempt_discard_merge",
      "external": true,
      "loc": "block/blk-core.c:645",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583937440,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
bool bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_discard_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584039440,
      "name": "bio_attempt_discard_merge",
      "external": true,
      "loc": "block/blk-core.c:645",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584039440,
      "name": "bio_attempt_discard_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
bool bio_attempt_discard_merge(struct request_queue * q, struct request * req, struct bio * bio)
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>enum bio_merge_status</code>
</li>
</ul>
</details>
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
