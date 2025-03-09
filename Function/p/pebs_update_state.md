# Function: <code>pebs_update_state</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct pmu * pmu)
```

```json
{
  "name": "pebs_update_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578908336,
      "name": "pebs_update_state",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:835",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_del",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578908336,
      "name": "pebs_update_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct pmu * pmu)
```

```json
{
  "name": "pebs_update_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578900368,
      "name": "pebs_update_state",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:853",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_del",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578900368,
      "name": "pebs_update_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct pmu * pmu)
```

```json
{
  "name": "pebs_update_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578902288,
      "name": "pebs_update_state",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:909",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_del",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578902288,
      "name": "pebs_update_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct pmu * pmu)
```

```json
{
  "name": "pebs_update_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578904272,
      "name": "pebs_update_state",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:911",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_del",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578904272,
      "name": "pebs_update_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct pmu * pmu)
```

```json
{
  "name": "pebs_update_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578905488,
      "name": "pebs_update_state",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:918",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_del",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578905488,
      "name": "pebs_update_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct perf_event * event, bool add)
```

```json
{
  "name": "pebs_update_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578907328,
      "name": "pebs_update_state",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1006",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_del",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578907328,
      "name": "pebs_update_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
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
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct perf_event * event, bool add)
```

```json
{
  "name": "pebs_update_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578909040,
      "name": "pebs_update_state",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1012",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_del",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578909040,
      "name": "pebs_update_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct perf_event * event, bool add)
```

```json
{
  "name": "pebs_update_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578914560,
      "name": "pebs_update_state",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1013",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_del",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578914560,
      "name": "pebs_update_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct perf_event * event, bool add)
```

```json
{
  "name": "pebs_update_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578912096,
      "name": "pebs_update_state",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1014",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_del",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578912096,
      "name": "pebs_update_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct perf_event * event, bool add)
```

```json
{
  "name": "pebs_update_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578915824,
      "name": "pebs_update_state",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1112",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_del",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578915824,
      "name": "pebs_update_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 727
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
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct perf_event * event, bool add)
```

```json
{
  "name": "pebs_update_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578919440,
      "name": "pebs_update_state",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1113",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_del",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578919440,
      "name": "pebs_update_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 727
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
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct perf_event * event, bool add)
```

```json
{
  "name": "pebs_update_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578926000,
      "name": "pebs_update_state",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1162",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_del",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578926000,
      "name": "pebs_update_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
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
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct perf_event * event, bool add)
```

```json
{
  "name": "pebs_update_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578942480,
      "name": "pebs_update_state",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1179",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_del",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578942480,
      "name": "pebs_update_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 794
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
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct perf_event * event, bool add)
```

```json
{
  "name": "pebs_update_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578940848,
      "name": "pebs_update_state",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1228",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_del",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578940848,
      "name": "pebs_update_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 601
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
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct perf_event * event, bool add)
```

```json
{
  "name": "pebs_update_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578964208,
      "name": "pebs_update_state",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1233",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_del",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578964208,
      "name": "pebs_update_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 601
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
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct perf_event * event, bool add)
```

```json
{
  "name": "pebs_update_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578909040,
      "name": "pebs_update_state",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1012",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_del",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578909040,
      "name": "pebs_update_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct perf_event * event, bool add)
```

```json
{
  "name": "pebs_update_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578904272,
      "name": "pebs_update_state",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1012",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_del",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578904272,
      "name": "pebs_update_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct perf_event * event, bool add)
```

```json
{
  "name": "pebs_update_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578908976,
      "name": "pebs_update_state",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1012",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_del",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578908976,
      "name": "pebs_update_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct perf_event * event, bool add)
```

```json
{
  "name": "pebs_update_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578909504,
      "name": "pebs_update_state",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1012",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_del",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578909504,
      "name": "pebs_update_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct pmu * pmu)
```
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct perf_event * event</code>
</li>
<li>
<b>Param added. </b>
<code>bool add</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pmu * pmu</code>
</li>
</ul>
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
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct perf_event * event, bool add)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct perf_event * event, bool add)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct perf_event * event, bool add)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void pebs_update_state(bool needed_cb, struct cpu_hw_events * cpuc, struct perf_event * event, bool add)
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
