# Function: <code>ioc_lookup_icq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582772720,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:317",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:get_request",
        "block/blk-ioc.c:ioc_create_icq",
        "block/cfq-iosched.c:cfq_allow_merge",
        "block/cfq-iosched.c:cfq_merge",
        "block/cfq-iosched.c:cfq_may_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582772720,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583051200,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:317",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:get_request",
        "block/blk-ioc.c:ioc_create_icq",
        "block/cfq-iosched.c:cfq_may_queue",
        "block/cfq-iosched.c:cfq_allow_bio_merge",
        "block/cfq-iosched.c:cfq_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583051200,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583156976,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:317",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:get_request",
        "block/blk-ioc.c:ioc_create_icq",
        "block/cfq-iosched.c:cfq_may_queue",
        "block/cfq-iosched.c:cfq_allow_bio_merge",
        "block/cfq-iosched.c:cfq_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583156976,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583214176,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:348",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:get_request",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc",
        "block/cfq-iosched.c:cfq_may_queue",
        "block/cfq-iosched.c:cfq_allow_bio_merge",
        "block/cfq-iosched.c:cfq_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583214176,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583390800,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:349",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:get_request",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc",
        "block/cfq-iosched.c:cfq_may_queue",
        "block/cfq-iosched.c:cfq_allow_bio_merge",
        "block/cfq-iosched.c:cfq_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583390800,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583600592,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:349",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:get_request",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc",
        "block/cfq-iosched.c:cfq_may_queue",
        "block/cfq-iosched.c:cfq_allow_bio_merge",
        "block/cfq-iosched.c:cfq_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583600592,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583706688,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:325",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583706688,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583895280,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:325",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583895280,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583998640,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:325",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583998640,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584387664,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:332",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387664,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584501808,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:332",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584501808,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584536224,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:332",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536224,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584947344,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:332",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584947344,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct io_cq * ioc_lookup_icq(struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585650848,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:328",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_find_get_icq",
        "block/blk-ioc.c:ioc_create_icq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585650848,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct io_cq * ioc_lookup_icq(struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586423968,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:328",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_find_get_icq",
        "block/blk-ioc.c:ioc_create_icq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586423968,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct io_cq * ioc_lookup_icq(struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586671520,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:324",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_find_get_icq",
        "block/blk-ioc.c:ioc_create_icq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586671520,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct io_cq * ioc_lookup_icq(struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586942416,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:324",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_find_get_icq",
        "block/blk-ioc.c:ioc_create_icq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586942416,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495826368,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:325",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495826368,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229176048,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:325",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229176048,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290016640,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:325",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290016640,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274960870,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:325",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274960870,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583967376,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:325",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583967376,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583904288,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:325",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583904288,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583951136,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:325",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583951136,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
struct io_cq * ioc_lookup_icq(struct io_context * ioc, struct request_queue * q)
```

```json
{
  "name": "ioc_lookup_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584053296,
      "name": "ioc_lookup_icq",
      "external": true,
      "loc": "block/blk-ioc.c:325",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584053296,
      "name": "ioc_lookup_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct io_context * ioc</code>
</li>
<li>
<b>Param reordered. </b>
<code>ioc, q</code> ➡️ <code>q</code>
</li>
</ul>
</details>
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
