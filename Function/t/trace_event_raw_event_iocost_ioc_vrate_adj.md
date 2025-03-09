# Function: <code>trace_event_raw_event_iocost_ioc_vrate_adj</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584157632,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "external": false,
      "loc": "include/trace/events/iocost.h:131",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584157632,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
void trace_event_raw_event_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32 * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584555472,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "external": false,
      "loc": "include/trace/events/iocost.h:131",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584555472,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32 * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages)
```

```json
{
  "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584669200,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "external": false,
      "loc": "include/trace/events/iocost.h:142",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584669200,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
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
void trace_event_raw_event_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32 * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages)
```

```json
{
  "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584697200,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "external": false,
      "loc": "include/trace/events/iocost.h:142",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584697200,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
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
void trace_event_raw_event_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32 * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages)
```

```json
{
  "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585121504,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "external": false,
      "loc": "include/trace/events/iocost.h:142",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585121504,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
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
void trace_event_raw_event_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32 * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages)
```

```json
{
  "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585858048,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "external": false,
      "loc": "include/trace/events/iocost.h:142",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585858048,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32 * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages)
```

```json
{
  "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586640016,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "external": false,
      "loc": "include/trace/events/iocost.h:142",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586640016,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 633
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
void trace_event_raw_event_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32 * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages)
```

```json
{
  "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586901008,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "external": false,
      "loc": "include/trace/events/iocost.h:142",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586901008,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
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
void trace_event_raw_event_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32 * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages)
```

```json
{
  "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587179040,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "external": false,
      "loc": "include/trace/events/iocost.h:142",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587179040,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
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
void trace_event_raw_event_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496006248,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "external": false,
      "loc": "include/trace/events/iocost.h:131",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496006248,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void trace_event_raw_event_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229354412,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "external": false,
      "loc": "include/trace/events/iocost.h:131",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229354412,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
void trace_event_raw_event_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290240960,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "external": false,
      "loc": "include/trace/events/iocost.h:131",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290240960,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
void trace_event_raw_event_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275104050,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "external": false,
      "loc": "include/trace/events/iocost.h:131",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275104050,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
void trace_event_raw_event_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584126368,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "external": false,
      "loc": "include/trace/events/iocost.h:131",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584126368,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
void trace_event_raw_event_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584062032,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "external": false,
      "loc": "include/trace/events/iocost.h:131",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584062032,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
void trace_event_raw_event_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584110128,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "external": false,
      "loc": "include/trace/events/iocost.h:131",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110128,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
void trace_event_raw_event_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584219424,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "external": false,
      "loc": "include/trace/events/iocost.h:131",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584219424,
      "name": "trace_event_raw_event_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32[2] * missed_ppm</code> ➡️ <code>u32 * missed_ppm</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nr_surpluses</code>
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
