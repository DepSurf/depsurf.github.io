# Function: <code>intel_pmu_check_num_counters</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void intel_pmu_check_num_counters(int * num_counters, int * num_counters_fixed, u64 * intel_ctrl, u64 fixed_mask)
```

```json
{
  "name": "intel_pmu_check_num_counters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591183002,
      "name": "intel_pmu_check_num_counters",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:5395",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591183002,
      "name": "intel_pmu_check_num_counters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void intel_pmu_check_num_counters(int * num_counters, int * num_counters_fixed, u64 * intel_ctrl, u64 fixed_mask)
```

```json
{
  "name": "intel_pmu_check_num_counters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592040184,
      "name": "intel_pmu_check_num_counters",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:5415",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592040184,
      "name": "intel_pmu_check_num_counters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void intel_pmu_check_num_counters(int * num_counters, int * num_counters_fixed, u64 * intel_ctrl, u64 fixed_mask)
```

```json
{
  "name": "intel_pmu_check_num_counters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593806390,
      "name": "intel_pmu_check_num_counters",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:5485",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593806390,
      "name": "intel_pmu_check_num_counters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void intel_pmu_check_num_counters(int * num_counters, int * num_counters_fixed, u64 * intel_ctrl, u64 fixed_mask)
```

```json
{
  "name": "intel_pmu_check_num_counters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pmu_check_num_counters",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:5611",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578916720,
      "name": "intel_pmu_check_num_counters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071595951616,
      "name": "intel_pmu_check_num_counters.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void intel_pmu_check_num_counters(int * num_counters, int * num_counters_fixed, u64 * intel_ctrl, u64 fixed_mask)
```

```json
{
  "name": "intel_pmu_check_num_counters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pmu_check_num_counters",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:5777",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578914304,
      "name": "intel_pmu_check_num_counters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071596468794,
      "name": "intel_pmu_check_num_counters.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void intel_pmu_check_num_counters(int * num_counters, int * num_counters_fixed, u64 * intel_ctrl, u64 fixed_mask)
```

```json
{
  "name": "intel_pmu_check_num_counters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pmu_check_num_counters",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:5964",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578936576,
      "name": "intel_pmu_check_num_counters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071597363861,
      "name": "intel_pmu_check_num_counters.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void intel_pmu_check_num_counters(int * num_counters, int * num_counters_fixed, u64 * intel_ctrl, u64 fixed_mask)
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
