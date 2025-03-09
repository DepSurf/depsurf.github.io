# Function: <code>perf_trace_qdisc_destroy</code>

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
void perf_trace_qdisc_destroy(void * __data, struct Qdisc * q)
```

```json
{
  "name": "perf_trace_qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589616960,
      "name": "perf_trace_qdisc_destroy",
      "external": false,
      "loc": "include/trace/events/qdisc.h:74",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589616960,
      "name": "perf_trace_qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void perf_trace_qdisc_destroy(void * __data, struct Qdisc * q)
```

```json
{
  "name": "perf_trace_qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_trace_qdisc_destroy",
      "external": false,
      "loc": "include/trace/events/qdisc.h:74",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589635536,
      "name": "perf_trace_qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
    },
    {
      "addr": 18446744071591632035,
      "name": "perf_trace_qdisc_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void perf_trace_qdisc_destroy(void * __data, struct Qdisc * q)
```

```json
{
  "name": "perf_trace_qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_trace_qdisc_destroy",
      "external": false,
      "loc": "include/trace/events/qdisc.h:74",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589524784,
      "name": "perf_trace_qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
    },
    {
      "addr": 18446744071591575404,
      "name": "perf_trace_qdisc_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void perf_trace_qdisc_destroy(void * __data, struct Qdisc * q)
```

```json
{
  "name": "perf_trace_qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_trace_qdisc_destroy",
      "external": false,
      "loc": "include/trace/events/qdisc.h:102",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590267664,
      "name": "perf_trace_qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
    },
    {
      "addr": 18446744071592705920,
      "name": "perf_trace_qdisc_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void perf_trace_qdisc_destroy(void * __data, struct Qdisc * q)
```

```json
{
  "name": "perf_trace_qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_trace_qdisc_destroy",
      "external": false,
      "loc": "include/trace/events/qdisc.h:102",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591841680,
      "name": "perf_trace_qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
    },
    {
      "addr": 18446744071594592125,
      "name": "perf_trace_qdisc_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void perf_trace_qdisc_destroy(void * __data, struct Qdisc * q)
```

```json
{
  "name": "perf_trace_qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593638224,
      "name": "perf_trace_qdisc_destroy",
      "external": false,
      "loc": "include/trace/events/qdisc.h:102",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593638224,
      "name": "perf_trace_qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
void perf_trace_qdisc_destroy(void * __data, struct Qdisc * q)
```

```json
{
  "name": "perf_trace_qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594113856,
      "name": "perf_trace_qdisc_destroy",
      "external": false,
      "loc": "include/trace/events/qdisc.h:102",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594113856,
      "name": "perf_trace_qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
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
void perf_trace_qdisc_destroy(void * __data, struct Qdisc * q)
```

```json
{
  "name": "perf_trace_qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594908784,
      "name": "perf_trace_qdisc_destroy",
      "external": false,
      "loc": "include/trace/events/qdisc.h:102",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594908784,
      "name": "perf_trace_qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 805
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
void perf_trace_qdisc_destroy(void * __data, struct Qdisc * q)
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
