# Function: <code>setup_pebs_fixed_sample_data</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void setup_pebs_fixed_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_fixed_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578909872,
      "name": "setup_pebs_fixed_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1296",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578909872,
      "name": "setup_pebs_fixed_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
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
void setup_pebs_fixed_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_fixed_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578911632,
      "name": "setup_pebs_fixed_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1339",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578911632,
      "name": "setup_pebs_fixed_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
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
void setup_pebs_fixed_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_fixed_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578917632,
      "name": "setup_pebs_fixed_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1340",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578917632,
      "name": "setup_pebs_fixed_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
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
void setup_pebs_fixed_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_fixed_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578914848,
      "name": "setup_pebs_fixed_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1345",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578914848,
      "name": "setup_pebs_fixed_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
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
void setup_pebs_fixed_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_fixed_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578918928,
      "name": "setup_pebs_fixed_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1444",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578918928,
      "name": "setup_pebs_fixed_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 926
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
void setup_pebs_fixed_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_fixed_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578922752,
      "name": "setup_pebs_fixed_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1453",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578922752,
      "name": "setup_pebs_fixed_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 943
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
void setup_pebs_fixed_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_fixed_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578929744,
      "name": "setup_pebs_fixed_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1511",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578929744,
      "name": "setup_pebs_fixed_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 963
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
void setup_pebs_fixed_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_fixed_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578946592,
      "name": "setup_pebs_fixed_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1549",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578946592,
      "name": "setup_pebs_fixed_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 955
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
void setup_pebs_fixed_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_fixed_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578945056,
      "name": "setup_pebs_fixed_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1606",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578945056,
      "name": "setup_pebs_fixed_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1023
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
void setup_pebs_fixed_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_fixed_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578968432,
      "name": "setup_pebs_fixed_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1611",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578968432,
      "name": "setup_pebs_fixed_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1031
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void setup_pebs_fixed_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_fixed_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578911632,
      "name": "setup_pebs_fixed_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1339",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578911632,
      "name": "setup_pebs_fixed_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
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
void setup_pebs_fixed_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_fixed_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578906928,
      "name": "setup_pebs_fixed_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1339",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578906928,
      "name": "setup_pebs_fixed_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
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
void setup_pebs_fixed_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_fixed_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578911568,
      "name": "setup_pebs_fixed_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1339",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578911568,
      "name": "setup_pebs_fixed_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
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
void setup_pebs_fixed_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_fixed_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578912096,
      "name": "setup_pebs_fixed_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1339",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578912096,
      "name": "setup_pebs_fixed_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void setup_pebs_fixed_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void setup_pebs_fixed_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void setup_pebs_fixed_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void setup_pebs_fixed_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void setup_pebs_fixed_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```
</details>
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
