# Function: <code>setup_pebs_adaptive_sample_data</code>

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
void setup_pebs_adaptive_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_adaptive_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578908880,
      "name": "setup_pebs_adaptive_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1465",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578908880,
      "name": "setup_pebs_adaptive_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
void setup_pebs_adaptive_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_adaptive_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578910640,
      "name": "setup_pebs_adaptive_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1508",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578910640,
      "name": "setup_pebs_adaptive_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
void setup_pebs_adaptive_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_adaptive_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578915920,
      "name": "setup_pebs_adaptive_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1509",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578915920,
      "name": "setup_pebs_adaptive_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
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
void setup_pebs_adaptive_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_adaptive_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578913408,
      "name": "setup_pebs_adaptive_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1514",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578913408,
      "name": "setup_pebs_adaptive_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
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
void setup_pebs_adaptive_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_adaptive_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578917440,
      "name": "setup_pebs_adaptive_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1616",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578917440,
      "name": "setup_pebs_adaptive_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1034
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
void setup_pebs_adaptive_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_adaptive_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_pebs_adaptive_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1625",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578921232,
      "name": "setup_pebs_adaptive_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1059
    },
    {
      "addr": 18446744071592042201,
      "name": "setup_pebs_adaptive_sample_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void setup_pebs_adaptive_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_adaptive_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_pebs_adaptive_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1683",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578928640,
      "name": "setup_pebs_adaptive_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1095
    },
    {
      "addr": 18446744071593808365,
      "name": "setup_pebs_adaptive_sample_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void setup_pebs_adaptive_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_adaptive_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_pebs_adaptive_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1733",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578945504,
      "name": "setup_pebs_adaptive_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
    },
    {
      "addr": 18446744071595952736,
      "name": "setup_pebs_adaptive_sample_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void setup_pebs_adaptive_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_adaptive_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_pebs_adaptive_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1787",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578943680,
      "name": "setup_pebs_adaptive_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1180
    },
    {
      "addr": 18446744071596469878,
      "name": "setup_pebs_adaptive_sample_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void setup_pebs_adaptive_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_adaptive_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_pebs_adaptive_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1792",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl",
        "arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967104,
      "name": "setup_pebs_adaptive_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1126
    },
    {
      "addr": 18446744071597365013,
      "name": "setup_pebs_adaptive_sample_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void setup_pebs_adaptive_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_adaptive_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578910640,
      "name": "setup_pebs_adaptive_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1508",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578910640,
      "name": "setup_pebs_adaptive_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
void setup_pebs_adaptive_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_adaptive_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578905936,
      "name": "setup_pebs_adaptive_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1508",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578905936,
      "name": "setup_pebs_adaptive_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
void setup_pebs_adaptive_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_adaptive_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578910576,
      "name": "setup_pebs_adaptive_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1508",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578910576,
      "name": "setup_pebs_adaptive_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
void setup_pebs_adaptive_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```

```json
{
  "name": "setup_pebs_adaptive_sample_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578911104,
      "name": "setup_pebs_adaptive_sample_data",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1508",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578911104,
      "name": "setup_pebs_adaptive_sample_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
void setup_pebs_adaptive_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
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
void setup_pebs_adaptive_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void setup_pebs_adaptive_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void setup_pebs_adaptive_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void setup_pebs_adaptive_sample_data(struct perf_event * event, struct pt_regs * iregs, void * __pebs, struct perf_sample_data * data, struct pt_regs * regs)
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
