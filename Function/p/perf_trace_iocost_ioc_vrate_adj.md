# Function: <code>perf_trace_iocost_ioc_vrate_adj</code>

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
void perf_trace_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "perf_trace_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584158848,
      "name": "perf_trace_iocost_ioc_vrate_adj",
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
      "addr": 18446744071584158848,
      "name": "perf_trace_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
void perf_trace_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32 * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "perf_trace_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584554912,
      "name": "perf_trace_iocost_ioc_vrate_adj",
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
      "addr": 18446744071584554912,
      "name": "perf_trace_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
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
void perf_trace_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32 * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages)
```

```json
{
  "name": "perf_trace_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584666960,
      "name": "perf_trace_iocost_ioc_vrate_adj",
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
      "addr": 18446744071584666960,
      "name": "perf_trace_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
void perf_trace_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32 * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages)
```

```json
{
  "name": "perf_trace_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584696640,
      "name": "perf_trace_iocost_ioc_vrate_adj",
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
      "addr": 18446744071584696640,
      "name": "perf_trace_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
void perf_trace_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32 * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages)
```

```json
{
  "name": "perf_trace_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585119792,
      "name": "perf_trace_iocost_ioc_vrate_adj",
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
      "addr": 18446744071585119792,
      "name": "perf_trace_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
void perf_trace_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32 * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages)
```

```json
{
  "name": "perf_trace_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585848336,
      "name": "perf_trace_iocost_ioc_vrate_adj",
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
      "addr": 18446744071585848336,
      "name": "perf_trace_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
void perf_trace_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32 * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages)
```

```json
{
  "name": "perf_trace_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586628688,
      "name": "perf_trace_iocost_ioc_vrate_adj",
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
      "addr": 18446744071586628688,
      "name": "perf_trace_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
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
void perf_trace_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32 * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages)
```

```json
{
  "name": "perf_trace_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586886528,
      "name": "perf_trace_iocost_ioc_vrate_adj",
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
      "addr": 18446744071586886528,
      "name": "perf_trace_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 738
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
void perf_trace_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32 * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages)
```

```json
{
  "name": "perf_trace_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587164464,
      "name": "perf_trace_iocost_ioc_vrate_adj",
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
      "addr": 18446744071587164464,
      "name": "perf_trace_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 738
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
void perf_trace_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "perf_trace_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496007736,
      "name": "perf_trace_iocost_ioc_vrate_adj",
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
      "addr": 18446603336496007736,
      "name": "perf_trace_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
void perf_trace_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "perf_trace_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229353896,
      "name": "perf_trace_iocost_ioc_vrate_adj",
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
      "addr": 3229353896,
      "name": "perf_trace_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
void perf_trace_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "perf_trace_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290242256,
      "name": "perf_trace_iocost_ioc_vrate_adj",
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
      "addr": 13835058055290242256,
      "name": "perf_trace_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
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
void perf_trace_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "perf_trace_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275103212,
      "name": "perf_trace_iocost_ioc_vrate_adj",
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
      "addr": 18446743936275103212,
      "name": "perf_trace_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
void perf_trace_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "perf_trace_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584127584,
      "name": "perf_trace_iocost_ioc_vrate_adj",
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
      "addr": 18446744071584127584,
      "name": "perf_trace_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
void perf_trace_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "perf_trace_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584063248,
      "name": "perf_trace_iocost_ioc_vrate_adj",
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
      "addr": 18446744071584063248,
      "name": "perf_trace_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
void perf_trace_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "perf_trace_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584111344,
      "name": "perf_trace_iocost_ioc_vrate_adj",
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
      "addr": 18446744071584111344,
      "name": "perf_trace_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
void perf_trace_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
```

```json
{
  "name": "perf_trace_iocost_ioc_vrate_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584224144,
      "name": "perf_trace_iocost_ioc_vrate_adj",
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
      "addr": 18446744071584224144,
      "name": "perf_trace_iocost_ioc_vrate_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
void perf_trace_iocost_ioc_vrate_adj(void * __data, struct ioc * ioc, u64 new_vrate, u32[2] * missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses)
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
