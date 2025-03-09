# Function: <code>bio_attempt_front_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool bio_attempt_front_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582755808,
      "name": "bio_attempt_front_merge",
      "external": true,
      "loc": "block/blk-core.c:1567",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-mq.c:blk_mq_attempt_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582755808,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool bio_attempt_front_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583033712,
      "name": "bio_attempt_front_merge",
      "external": true,
      "loc": "block/blk-core.c:1528",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq.c:blk_sq_make_request",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583033712,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool bio_attempt_front_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583138656,
      "name": "bio_attempt_front_merge",
      "external": true,
      "loc": "block/blk-core.c:1501",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq.c:blk_sq_make_request",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583138656,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
bool bio_attempt_front_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583195584,
      "name": "bio_attempt_front_merge",
      "external": true,
      "loc": "block/blk-core.c:1604",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583195584,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
bool bio_attempt_front_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583372800,
      "name": "bio_attempt_front_merge",
      "external": true,
      "loc": "block/blk-core.c:1724",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583372800,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool bio_attempt_front_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583582320,
      "name": "bio_attempt_front_merge",
      "external": true,
      "loc": "block/blk-core.c:1821",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge",
        "block/blk-mq-sched.c:blk_mq_sched_try_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583582320,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
bool bio_attempt_front_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583692832,
      "name": "bio_attempt_front_merge",
      "external": true,
      "loc": "block/blk-core.c:618",
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
      "addr": 18446744071583692832,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
bool bio_attempt_front_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583881520,
      "name": "bio_attempt_front_merge",
      "external": true,
      "loc": "block/blk-core.c:616",
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
      "addr": 18446744071583881520,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
bool bio_attempt_front_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583984688,
      "name": "bio_attempt_front_merge",
      "external": true,
      "loc": "block/blk-core.c:621",
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
      "addr": 18446744071583984688,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
bool bio_attempt_front_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584373200,
      "name": "bio_attempt_front_merge",
      "external": true,
      "loc": "block/blk-core.c:675",
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
      "addr": 18446744071584373200,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
enum bio_merge_status bio_attempt_front_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584517872,
      "name": "bio_attempt_front_merge",
      "external": false,
      "loc": "block/blk-merge.c:957",
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
      "addr": 18446744071584517872,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
enum bio_merge_status bio_attempt_front_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584549920,
      "name": "bio_attempt_front_merge",
      "external": false,
      "loc": "block/blk-merge.c:960",
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
      "addr": 18446744071584549920,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
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
enum bio_merge_status bio_attempt_front_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584961232,
      "name": "bio_attempt_front_merge",
      "external": false,
      "loc": "block/blk-merge.c:943",
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
      "addr": 18446744071584961232,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 842
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
enum bio_merge_status bio_attempt_front_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585665216,
      "name": "bio_attempt_front_merge",
      "external": false,
      "loc": "block/blk-merge.c:940",
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
      "addr": 18446744071585665216,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
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
enum bio_merge_status bio_attempt_front_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586440752,
      "name": "bio_attempt_front_merge",
      "external": false,
      "loc": "block/blk-merge.c:1007",
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
      "addr": 18446744071586440752,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 845
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
enum bio_merge_status bio_attempt_front_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586687888,
      "name": "bio_attempt_front_merge",
      "external": false,
      "loc": "block/blk-merge.c:1003",
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
      "addr": 18446744071586687888,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 845
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
enum bio_merge_status bio_attempt_front_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586959216,
      "name": "bio_attempt_front_merge",
      "external": false,
      "loc": "block/blk-merge.c:999",
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
      "addr": 18446744071586959216,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 853
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
bool bio_attempt_front_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495809856,
      "name": "bio_attempt_front_merge",
      "external": true,
      "loc": "block/blk-core.c:621",
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
      "addr": 18446603336495809856,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
bool bio_attempt_front_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229161404,
      "name": "bio_attempt_front_merge",
      "external": true,
      "loc": "block/blk-core.c:621",
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
      "addr": 3229161404,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
bool bio_attempt_front_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289996000,
      "name": "bio_attempt_front_merge",
      "external": true,
      "loc": "block/blk-core.c:621",
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
      "addr": 13835058055289996000,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
bool bio_attempt_front_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274947316,
      "name": "bio_attempt_front_merge",
      "external": true,
      "loc": "block/blk-core.c:621",
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
      "addr": 18446743936274947316,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
bool bio_attempt_front_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583953424,
      "name": "bio_attempt_front_merge",
      "external": true,
      "loc": "block/blk-core.c:621",
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
      "addr": 18446744071583953424,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
bool bio_attempt_front_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583890352,
      "name": "bio_attempt_front_merge",
      "external": true,
      "loc": "block/blk-core.c:621",
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
      "addr": 18446744071583890352,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
bool bio_attempt_front_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583937184,
      "name": "bio_attempt_front_merge",
      "external": true,
      "loc": "block/blk-core.c:621",
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
      "addr": 18446744071583937184,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
bool bio_attempt_front_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_front_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584039168,
      "name": "bio_attempt_front_merge",
      "external": true,
      "loc": "block/blk-core.c:621",
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
      "addr": 18446744071584039168,
      "name": "bio_attempt_front_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int nr_segs</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue * q</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, req, bio</code> ➡️ <code>req, bio, nr_segs</code>
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
