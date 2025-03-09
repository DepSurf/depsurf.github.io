# Function: <code>bio_attempt_back_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool bio_attempt_back_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582755552,
      "name": "bio_attempt_back_merge",
      "external": true,
      "loc": "block/blk-core.c:1545",
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
      "addr": 18446744071582755552,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
bool bio_attempt_back_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583033456,
      "name": "bio_attempt_back_merge",
      "external": true,
      "loc": "block/blk-core.c:1506",
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
      "addr": 18446744071583033456,
      "name": "bio_attempt_back_merge",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool bio_attempt_back_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583138416,
      "name": "bio_attempt_back_merge",
      "external": true,
      "loc": "block/blk-core.c:1479",
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
      "addr": 18446744071583138416,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
bool bio_attempt_back_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583195344,
      "name": "bio_attempt_back_merge",
      "external": true,
      "loc": "block/blk-core.c:1582",
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
      "addr": 18446744071583195344,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
bool bio_attempt_back_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583372560,
      "name": "bio_attempt_back_merge",
      "external": true,
      "loc": "block/blk-core.c:1702",
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
      "addr": 18446744071583372560,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
bool bio_attempt_back_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583582080,
      "name": "bio_attempt_back_merge",
      "external": true,
      "loc": "block/blk-core.c:1799",
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
      "addr": 18446744071583582080,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
bool bio_attempt_back_merge(struct request_queue * q, struct request * req, struct bio * bio)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583692624,
      "name": "bio_attempt_back_merge",
      "external": true,
      "loc": "block/blk-core.c:597",
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
      "addr": 18446744071583692624,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
bool bio_attempt_back_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583881296,
      "name": "bio_attempt_back_merge",
      "external": true,
      "loc": "block/blk-core.c:595",
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
      "addr": 18446744071583881296,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
bool bio_attempt_back_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583984448,
      "name": "bio_attempt_back_merge",
      "external": true,
      "loc": "block/blk-core.c:599",
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
      "addr": 18446744071583984448,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
bool bio_attempt_back_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584372944,
      "name": "bio_attempt_back_merge",
      "external": true,
      "loc": "block/blk-core.c:651",
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
      "addr": 18446744071584372944,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
enum bio_merge_status bio_attempt_back_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584517664,
      "name": "bio_attempt_back_merge",
      "external": false,
      "loc": "block/blk-merge.c:933",
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
      "addr": 18446744071584517664,
      "name": "bio_attempt_back_merge",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_back_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584549712,
      "name": "bio_attempt_back_merge",
      "external": false,
      "loc": "block/blk-merge.c:936",
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
      "addr": 18446744071584549712,
      "name": "bio_attempt_back_merge",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
enum bio_merge_status bio_attempt_back_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584961024,
      "name": "bio_attempt_back_merge",
      "external": false,
      "loc": "block/blk-merge.c:919",
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
      "addr": 18446744071584961024,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
enum bio_merge_status bio_attempt_back_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585664976,
      "name": "bio_attempt_back_merge",
      "external": false,
      "loc": "block/blk-merge.c:916",
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
      "addr": 18446744071585664976,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
enum bio_merge_status bio_attempt_back_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586440416,
      "name": "bio_attempt_back_merge",
      "external": false,
      "loc": "block/blk-merge.c:981",
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
      "addr": 18446744071586440416,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
enum bio_merge_status bio_attempt_back_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586687552,
      "name": "bio_attempt_back_merge",
      "external": false,
      "loc": "block/blk-merge.c:977",
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
      "addr": 18446744071586687552,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
enum bio_merge_status bio_attempt_back_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586958880,
      "name": "bio_attempt_back_merge",
      "external": false,
      "loc": "block/blk-merge.c:973",
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
      "addr": 18446744071586958880,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
bool bio_attempt_back_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495809528,
      "name": "bio_attempt_back_merge",
      "external": true,
      "loc": "block/blk-core.c:599",
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
      "addr": 18446603336495809528,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
bool bio_attempt_back_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229161108,
      "name": "bio_attempt_back_merge",
      "external": true,
      "loc": "block/blk-core.c:599",
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
      "addr": 3229161108,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
bool bio_attempt_back_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289995600,
      "name": "bio_attempt_back_merge",
      "external": true,
      "loc": "block/blk-core.c:599",
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
      "addr": 13835058055289995600,
      "name": "bio_attempt_back_merge",
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
bool bio_attempt_back_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274947066,
      "name": "bio_attempt_back_merge",
      "external": true,
      "loc": "block/blk-core.c:599",
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
      "addr": 18446743936274947066,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
bool bio_attempt_back_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583953184,
      "name": "bio_attempt_back_merge",
      "external": true,
      "loc": "block/blk-core.c:599",
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
      "addr": 18446744071583953184,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
bool bio_attempt_back_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583890112,
      "name": "bio_attempt_back_merge",
      "external": true,
      "loc": "block/blk-core.c:599",
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
      "addr": 18446744071583890112,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
bool bio_attempt_back_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583936944,
      "name": "bio_attempt_back_merge",
      "external": true,
      "loc": "block/blk-core.c:599",
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
      "addr": 18446744071583936944,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
bool bio_attempt_back_merge(struct request * req, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "bio_attempt_back_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584038896,
      "name": "bio_attempt_back_merge",
      "external": true,
      "loc": "block/blk-core.c:599",
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
      "addr": 18446744071584038896,
      "name": "bio_attempt_back_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
