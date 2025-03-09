# Function: <code>start_per_cpu_kthreads</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "start_per_cpu_kthreads",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580904676,
      "name": "start_per_cpu_kthreads",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:579",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start"
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
  "name": "start_per_cpu_kthreads",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581141002,
      "name": "start_per_cpu_kthreads",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:575",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "start_per_cpu_kthreads",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581452602,
      "name": "start_per_cpu_kthreads",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:575",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int start_per_cpu_kthreads(struct trace_array * tr)
```

```json
{
  "name": "start_per_cpu_kthreads",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581549690,
      "name": "start_per_cpu_kthreads",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:579",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581561424,
      "name": "start_per_cpu_kthreads",
      "external": false,
      "loc": "kernel/trace/trace_osnoise.c:2034",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_osnoise.c:osnoise_workload_start",
        "kernel/trace/trace_osnoise.c:osnoise_cpus_write",
        "kernel/trace/trace_osnoise.c:osnoise_options_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561424,
      "name": "start_per_cpu_kthreads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int start_per_cpu_kthreads(struct trace_array * tr)
```

```json
{
  "name": "start_per_cpu_kthreads",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581661914,
      "name": "start_per_cpu_kthreads",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:579",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581673632,
      "name": "start_per_cpu_kthreads",
      "external": false,
      "loc": "kernel/trace/trace_osnoise.c:2034",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_osnoise.c:osnoise_workload_start",
        "kernel/trace/trace_osnoise.c:osnoise_cpus_write",
        "kernel/trace/trace_osnoise.c:osnoise_options_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581673632,
      "name": "start_per_cpu_kthreads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int start_per_cpu_kthreads(struct trace_array * tr)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
