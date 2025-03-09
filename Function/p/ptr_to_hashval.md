# Function: <code>ptr_to_hashval</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ptr_to_hashval(const void * ptr, long unsigned int * hashval_out)
```

```json
{
  "name": "ptr_to_hashval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585110208,
      "name": "ptr_to_hashval",
      "external": true,
      "loc": "lib/vsprintf.c:786",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:perf_trace_rss_stat",
        "mm/slab_common.c:trace_event_raw_event_rss_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585110208,
      "name": "ptr_to_hashval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int ptr_to_hashval(const void * ptr, long unsigned int * hashval_out)
```

```json
{
  "name": "ptr_to_hashval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585259392,
      "name": "ptr_to_hashval",
      "external": true,
      "loc": "lib/vsprintf.c:789",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:perf_trace_rss_stat",
        "mm/slab_common.c:trace_event_raw_event_rss_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585259392,
      "name": "ptr_to_hashval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int ptr_to_hashval(const void * ptr, long unsigned int * hashval_out)
```

```json
{
  "name": "ptr_to_hashval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585142992,
      "name": "ptr_to_hashval",
      "external": true,
      "loc": "lib/vsprintf.c:815",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:perf_trace_rss_stat",
        "mm/slab_common.c:trace_event_raw_event_rss_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585142992,
      "name": "ptr_to_hashval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int ptr_to_hashval(const void * ptr, long unsigned int * hashval_out)
```

```json
{
  "name": "ptr_to_hashval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585593440,
      "name": "ptr_to_hashval",
      "external": true,
      "loc": "lib/vsprintf.c:816",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core_sched.c:sched_core_share_pid",
        "mm/slab_common.c:perf_trace_rss_stat",
        "mm/slab_common.c:trace_event_raw_event_rss_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585593440,
      "name": "ptr_to_hashval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int ptr_to_hashval(const void * ptr, long unsigned int * hashval_out)
```

```json
{
  "name": "ptr_to_hashval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586749440,
      "name": "ptr_to_hashval",
      "external": true,
      "loc": "lib/vsprintf.c:799",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "mm/slab_common.c:perf_trace_rss_stat",
        "mm/slab_common.c:trace_event_raw_event_rss_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586749440,
      "name": "ptr_to_hashval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int ptr_to_hashval(const void * ptr, long unsigned int * hashval_out)
```

```json
{
  "name": "ptr_to_hashval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptr_to_hashval",
      "external": true,
      "loc": "lib/vsprintf.c:800",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "mm/slab_common.c:perf_trace_rss_stat",
        "mm/slab_common.c:trace_event_raw_event_rss_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596375048,
      "name": "ptr_to_hashval.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071595913136,
      "name": "ptr_to_hashval",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int ptr_to_hashval(const void * ptr, long unsigned int * hashval_out)
```

```json
{
  "name": "ptr_to_hashval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptr_to_hashval",
      "external": true,
      "loc": "lib/vsprintf.c:800",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "mm/slab_common.c:perf_trace_rss_stat",
        "mm/slab_common.c:trace_event_raw_event_rss_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596904569,
      "name": "ptr_to_hashval.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071596430912,
      "name": "ptr_to_hashval",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int ptr_to_hashval(const void * ptr, long unsigned int * hashval_out)
```

```json
{
  "name": "ptr_to_hashval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptr_to_hashval",
      "external": true,
      "loc": "lib/vsprintf.c:802",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "mm/slab_common.c:perf_trace_rss_stat",
        "mm/slab_common.c:trace_event_raw_event_rss_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597829662,
      "name": "ptr_to_hashval.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071597326272,
      "name": "ptr_to_hashval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ptr_to_hashval(const void * ptr, long unsigned int * hashval_out)
```
</details>
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
