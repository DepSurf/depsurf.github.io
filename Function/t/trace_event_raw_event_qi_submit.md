# Function: <code>trace_event_raw_event_qi_submit</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void trace_event_raw_event_qi_submit(void * __data, struct intel_iommu * iommu, u64 qw0, u64 qw1, u64 qw2, u64 qw3)
```

```json
{
  "name": "trace_event_raw_event_qi_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_event_raw_event_qi_submit",
      "external": false,
      "loc": "include/trace/events/intel_iommu.h:18",
      "file": "drivers/iommu/intel/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586805344,
      "name": "trace_event_raw_event_qi_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
    },
    {
      "addr": 18446744071591421479,
      "name": "trace_event_raw_event_qi_submit.cold",
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
void trace_event_raw_event_qi_submit(void * __data, struct intel_iommu * iommu, u64 qw0, u64 qw1, u64 qw2, u64 qw3)
```

```json
{
  "name": "trace_event_raw_event_qi_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_event_raw_event_qi_submit",
      "external": false,
      "loc": "include/trace/events/intel_iommu.h:20",
      "file": "drivers/iommu/intel/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587364336,
      "name": "trace_event_raw_event_qi_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
    },
    {
      "addr": 18446744071592477939,
      "name": "trace_event_raw_event_qi_submit.cold",
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
void trace_event_raw_event_qi_submit(void * __data, struct intel_iommu * iommu, u64 qw0, u64 qw1, u64 qw2, u64 qw3)
```

```json
{
  "name": "trace_event_raw_event_qi_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_event_raw_event_qi_submit",
      "external": false,
      "loc": "include/trace/events/intel_iommu.h:20",
      "file": "drivers/iommu/intel/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588676016,
      "name": "trace_event_raw_event_qi_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
    },
    {
      "addr": 18446744071594347019,
      "name": "trace_event_raw_event_qi_submit.cold",
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
void trace_event_raw_event_qi_submit(void * __data, struct intel_iommu * iommu, u64 qw0, u64 qw1, u64 qw2, u64 qw3)
```

```json
{
  "name": "trace_event_raw_event_qi_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590149872,
      "name": "trace_event_raw_event_qi_submit",
      "external": false,
      "loc": "drivers/iommu/intel/trace.h:21",
      "file": "drivers/iommu/intel/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590149872,
      "name": "trace_event_raw_event_qi_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
void trace_event_raw_event_qi_submit(void * __data, struct intel_iommu * iommu, u64 qw0, u64 qw1, u64 qw2, u64 qw3)
```

```json
{
  "name": "trace_event_raw_event_qi_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590464224,
      "name": "trace_event_raw_event_qi_submit",
      "external": false,
      "loc": "drivers/iommu/intel/trace.h:21",
      "file": "drivers/iommu/intel/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590464224,
      "name": "trace_event_raw_event_qi_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
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
void trace_event_raw_event_qi_submit(void * __data, struct intel_iommu * iommu, u64 qw0, u64 qw1, u64 qw2, u64 qw3)
```

```json
{
  "name": "trace_event_raw_event_qi_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590814752,
      "name": "trace_event_raw_event_qi_submit",
      "external": false,
      "loc": "drivers/iommu/intel/trace.h:21",
      "file": "drivers/iommu/intel/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590814752,
      "name": "trace_event_raw_event_qi_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void trace_event_raw_event_qi_submit(void * __data, struct intel_iommu * iommu, u64 qw0, u64 qw1, u64 qw2, u64 qw3)
```
</details>
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
