# Function: <code>blk_mq_map_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx * blk_mq_map_queue(struct request_queue * q, const int cpu)
```

```json
{
  "name": "blk_mq_map_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582788880,
      "name": "blk_mq_map_queue",
      "external": true,
      "loc": "block/blk-mq.c:1410",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582788880,
      "name": "blk_mq_map_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct blk_mq_hw_ctx * blk_mq_map_queue(struct request_queue * q, const int cpu)
```

```json
{
  "name": "blk_mq_map_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583066384,
      "name": "blk_mq_map_queue",
      "external": true,
      "loc": "block/blk-mq.c:1476",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583066384,
      "name": "blk_mq_map_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583140271,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:47",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_peek_request",
        "block/blk-core.c:__blk_drain_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583151874,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:47",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-flush.c:blk_flush_complete_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583186437,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:47",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_map_request",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:blk_mq_insert_request",
        "block/blk-mq.c:blk_mq_free_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583193388,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:47",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_unique_tag"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583197322,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:66",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_peek_request",
        "block/blk-core.c:__blk_drain_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583209306,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:66",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-flush.c:blk_flush_complete_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583247977,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:66",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_request_bypass_insert",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_get_driver_tag",
        "block/blk-mq.c:blk_mq_free_request",
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583250013,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:66",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_unique_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583259855,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:66",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583408365,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:66",
      "file": "block/blk-mq-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583371719,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:68",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_peek_request",
        "block/blk-core.c:__blk_drain_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583385914,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:68",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-flush.c:blk_flush_complete_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583427108,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:68",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_request_bypass_insert",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_get_driver_tag",
        "block/blk-mq.c:blk_mq_free_request",
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583429197,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:68",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_unique_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583439423,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:68",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583587949,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:68",
      "file": "block/blk-mq-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583581239,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:74",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_peek_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583595891,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:74",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-flush.c:blk_flush_complete_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583638375,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:74",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_request_bypass_insert",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_get_driver_tag",
        "block/blk-mq.c:blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583640440,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:74",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_unique_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583650709,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:74",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583804792,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:74",
      "file": "block/blk-mq-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583702442,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:101",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583729150,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:101",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583748190,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:101",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583756429,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:101",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
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
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:102",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583916078,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:102",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583937354,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:102",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583945547,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:102",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
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
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584019315,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584040826,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584049083,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
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
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584383739,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:102",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584410935,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:102",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_alloc_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584436041,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:102",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584445038,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:102",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
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
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584497723,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:104",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584527450,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:104",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_alloc_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584552446,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:104",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584561399,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:104",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
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
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584532394,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:105",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584559302,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:105",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_alloc_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584585262,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:105",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584594351,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:105",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584943242,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:105",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584970790,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:105",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_alloc_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584999484,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:105",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585008927,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:105",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585645592,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:109",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585680861,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:109",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_delay_run_hw_queues",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:__blk_mq_alloc_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585712791,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:109",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585724599,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:109",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_bio_merge"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586417832,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:109",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586452939,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:109",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_alloc_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586493063,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:109",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586505735,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:109",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_bio_merge"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586665169,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:105",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586715773,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:105",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_alloc_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586740647,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:105",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586752839,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:105",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_bio_merge"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586936284,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:105",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586987741,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:105",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_alloc_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587012727,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:105",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587025047,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:105",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_bio_merge"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495855688,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495875412,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495885768,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
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
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229170644,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 3229198608,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 3229221308,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 3229230476,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
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
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290010252,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290046060,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290076524,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290090076,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
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
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274956350,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274979154,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274998492,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275006872,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
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
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583988051,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584009562,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584017819,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
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
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583923907,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583945386,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583953627,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
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
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583971811,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583993322,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584001579,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
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
  "name": "blk_mq_map_queue",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584075591,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584095626,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584103948,
      "name": "blk_mq_map_queue",
      "external": false,
      "loc": "block/blk-mq.h:103",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
struct blk_mq_hw_ctx * blk_mq_map_queue(struct request_queue * q, const int cpu)
```
</details>
</li>
</ul>
