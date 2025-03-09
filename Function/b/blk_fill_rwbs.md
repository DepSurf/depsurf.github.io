# Function: <code>blk_fill_rwbs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_fill_rwbs(char * rwbs, u32 rw, int bytes)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580265408,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1776",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_with_error",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_bio_merge",
        "block/blk-core.c:trace_event_raw_event_block_bio_queue",
        "block/blk-core.c:trace_event_raw_event_block_bio_bounce",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_get_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_with_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580265408,
      "name": "blk_fill_rwbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void blk_fill_rwbs(char * rwbs, int op, u32 rw, int bytes)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580308672,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1780",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_with_error",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_get_rq",
        "block/blk-core.c:trace_event_raw_event_block_bio_queue",
        "block/blk-core.c:trace_event_raw_event_block_bio_merge",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_bounce",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_with_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580308672,
      "name": "blk_fill_rwbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void blk_fill_rwbs(char * rwbs, unsigned int op, int bytes)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580354832,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1780",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_with_error",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_get_rq",
        "block/blk-core.c:trace_event_raw_event_block_bio_queue",
        "block/blk-core.c:trace_event_raw_event_block_bio_merge",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_bounce",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_with_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580354832,
      "name": "blk_fill_rwbs",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void blk_fill_rwbs(char * rwbs, unsigned int op, int bytes)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580367280,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1733",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_get_rq",
        "block/blk-core.c:trace_event_raw_event_block_bio_queue",
        "block/blk-core.c:trace_event_raw_event_block_bio_merge",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_bounce",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580367280,
      "name": "blk_fill_rwbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void blk_fill_rwbs(char * rwbs, unsigned int op, int bytes)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580420976,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1888",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_get_rq",
        "block/blk-core.c:trace_event_raw_event_block_bio_queue",
        "block/blk-core.c:trace_event_raw_event_block_bio_merge",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_bounce",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420976,
      "name": "blk_fill_rwbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
void blk_fill_rwbs(char * rwbs, unsigned int op, int bytes)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580482816,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1892",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_get_rq",
        "block/blk-core.c:trace_event_raw_event_block_bio_queue",
        "block/blk-core.c:trace_event_raw_event_block_bio_merge",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_bounce",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580482816,
      "name": "blk_fill_rwbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blk_fill_rwbs(char * rwbs, unsigned int op, int bytes)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580538064,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1880",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_get_rq",
        "block/blk-core.c:trace_event_raw_event_block_bio_queue",
        "block/blk-core.c:trace_event_raw_event_block_bio_merge",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_bounce",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580538064,
      "name": "blk_fill_rwbs",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void blk_fill_rwbs(char * rwbs, unsigned int op, int bytes)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580594704,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1875",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_get_rq",
        "block/blk-core.c:trace_event_raw_event_block_bio_queue",
        "block/blk-core.c:trace_event_raw_event_block_bio_merge",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_bounce",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580594704,
      "name": "blk_fill_rwbs",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void blk_fill_rwbs(char * rwbs, unsigned int op, int bytes)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580641792,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1930",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_get_rq",
        "block/blk-core.c:trace_event_raw_event_block_bio_queue",
        "block/blk-core.c:trace_event_raw_event_block_bio_merge",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_bounce",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641792,
      "name": "blk_fill_rwbs",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void blk_fill_rwbs(char * rwbs, unsigned int op, int bytes)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580742976,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1958",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_get_rq",
        "block/blk-core.c:trace_event_raw_event_block_bio_queue",
        "block/blk-core.c:trace_event_raw_event_block_bio_merge",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_bounce",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580742976,
      "name": "blk_fill_rwbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
void blk_fill_rwbs(char * rwbs, unsigned int op, int bytes)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580731872,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1868",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_bio",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_bio",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580731872,
      "name": "blk_fill_rwbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void blk_fill_rwbs(char * rwbs, unsigned int op)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580736784,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1877",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_bio",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_bio",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580736784,
      "name": "blk_fill_rwbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void blk_fill_rwbs(char * rwbs, unsigned int op)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580919520,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1895",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_bio",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_bio",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919520,
      "name": "blk_fill_rwbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void blk_fill_rwbs(char * rwbs, unsigned int op)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581157376,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1895",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_bio",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_completion",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_bio",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_completion",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581157376,
      "name": "blk_fill_rwbs",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void blk_fill_rwbs(char * rwbs, blk_opf_t opf)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581470912,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1880",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_bio",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_completion",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_bio",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_completion",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581470912,
      "name": "blk_fill_rwbs",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void blk_fill_rwbs(char * rwbs, blk_opf_t opf)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581588880,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1876",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_bio",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_completion",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_bio",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_completion",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588880,
      "name": "blk_fill_rwbs",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void blk_fill_rwbs(char * rwbs, blk_opf_t opf)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581701232,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1876",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_bio",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_completion",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_bio",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_completion",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581701232,
      "name": "blk_fill_rwbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
void blk_fill_rwbs(char * rwbs, unsigned int op, int bytes)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491944168,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1930",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_get_rq",
        "block/blk-core.c:trace_event_raw_event_block_bio_queue",
        "block/blk-core.c:trace_event_raw_event_block_bio_merge",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_bounce",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491944168,
      "name": "blk_fill_rwbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void blk_fill_rwbs(char * rwbs, unsigned int op, int bytes)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225880492,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1930",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_get_rq",
        "block/blk-core.c:trace_event_raw_event_block_bio_queue",
        "block/blk-core.c:trace_event_raw_event_block_bio_merge",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_bounce",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225880492,
      "name": "blk_fill_rwbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void blk_fill_rwbs(char * rwbs, unsigned int op, int bytes)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285047344,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1930",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_get_rq",
        "block/blk-core.c:trace_event_raw_event_block_bio_queue",
        "block/blk-core.c:trace_event_raw_event_block_bio_merge",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_bounce",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285047344,
      "name": "blk_fill_rwbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
void blk_fill_rwbs(char * rwbs, unsigned int op, int bytes)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272220772,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1930",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_get_rq",
        "block/blk-core.c:trace_event_raw_event_block_bio_queue",
        "block/blk-core.c:trace_event_raw_event_block_bio_merge",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_bounce",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272220772,
      "name": "blk_fill_rwbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void blk_fill_rwbs(char * rwbs, unsigned int op, int bytes)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580610592,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1930",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_get_rq",
        "block/blk-core.c:trace_event_raw_event_block_bio_queue",
        "block/blk-core.c:trace_event_raw_event_block_bio_merge",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_bounce",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580610592,
      "name": "blk_fill_rwbs",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void blk_fill_rwbs(char * rwbs, unsigned int op, int bytes)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580556912,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1930",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_get_rq",
        "block/blk-core.c:trace_event_raw_event_block_bio_queue",
        "block/blk-core.c:trace_event_raw_event_block_bio_merge",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_bounce",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580556912,
      "name": "blk_fill_rwbs",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void blk_fill_rwbs(char * rwbs, unsigned int op, int bytes)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580601840,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1930",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_get_rq",
        "block/blk-core.c:trace_event_raw_event_block_bio_queue",
        "block/blk-core.c:trace_event_raw_event_block_bio_merge",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_bounce",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580601840,
      "name": "blk_fill_rwbs",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void blk_fill_rwbs(char * rwbs, unsigned int op, int bytes)
```

```json
{
  "name": "blk_fill_rwbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580658880,
      "name": "blk_fill_rwbs",
      "external": true,
      "loc": "kernel/trace/blktrace.c:1930",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:perf_trace_block_rq_remap",
        "block/blk-core.c:perf_trace_block_bio_remap",
        "block/blk-core.c:perf_trace_block_split",
        "block/blk-core.c:perf_trace_block_get_rq",
        "block/blk-core.c:perf_trace_block_bio_queue",
        "block/blk-core.c:perf_trace_block_bio_merge",
        "block/blk-core.c:perf_trace_block_bio_complete",
        "block/blk-core.c:perf_trace_block_bio_bounce",
        "block/blk-core.c:perf_trace_block_rq",
        "block/blk-core.c:perf_trace_block_rq_complete",
        "block/blk-core.c:perf_trace_block_rq_requeue",
        "block/blk-core.c:trace_event_raw_event_block_rq_remap",
        "block/blk-core.c:trace_event_raw_event_block_bio_remap",
        "block/blk-core.c:trace_event_raw_event_block_split",
        "block/blk-core.c:trace_event_raw_event_block_get_rq",
        "block/blk-core.c:trace_event_raw_event_block_bio_queue",
        "block/blk-core.c:trace_event_raw_event_block_bio_merge",
        "block/blk-core.c:trace_event_raw_event_block_bio_complete",
        "block/blk-core.c:trace_event_raw_event_block_bio_bounce",
        "block/blk-core.c:trace_event_raw_event_block_rq",
        "block/blk-core.c:trace_event_raw_event_block_rq_complete",
        "block/blk-core.c:trace_event_raw_event_block_rq_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580658880,
      "name": "blk_fill_rwbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int op</code>
</li>
<li>
<b>Param reordered. </b>
<code>rwbs, rw, bytes</code> ➡️ <code>rwbs, op, rw, bytes</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 rw</code>
</li>
<li>
<b>Param reordered. </b>
<code>rwbs, op, rw, bytes</code> ➡️ <code>rwbs, op, bytes</code>
</li>
<li>
<b>Param type changed. </b>
<code>int op</code> ➡️ <code>unsigned int op</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int bytes</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_opf_t opf</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int op</code>
</li>
</ul>
</details>
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
