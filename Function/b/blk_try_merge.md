# Function: <code>blk_try_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582784624,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:778",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq.c:blk_mq_attempt_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582784624,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583063056,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:810",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq.c:blk_sq_make_request",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583063056,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583170224,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:801",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq.c:blk_sq_make_request",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583170224,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583227472,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:811",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583227472,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583404144,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:812",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583404144,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583614400,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:843",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583614400,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583719808,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:886",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583719808,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583907952,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:833",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583907952,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584011168,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:886",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584011168,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584403248,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:887",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584403248,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584518597,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:906",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584519408,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584551205,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:909",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584552032,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584962533,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:892",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584963360,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585666501,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:889",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585667200,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586442101,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:954",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586442864,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586689253,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:950",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586690016,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586960597,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:946",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586961360,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495840848,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:886",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495840848,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229188956,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:886",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229188956,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290033008,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:886",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290033008,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274971502,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:886",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274971502,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583979904,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:886",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583979904,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583915824,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:886",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583915824,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583963664,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:886",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583963664,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
enum elv_merge blk_try_merge(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_try_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584065744,
      "name": "blk_try_merge",
      "external": true,
      "loc": "block/blk-merge.c:886",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_merge",
        "block/blk-core.c:blk_attempt_plug_merge",
        "block/blk-mq-sched.c:blk_mq_bio_list_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584065744,
      "name": "blk_try_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>enum elv_merge</code>
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
