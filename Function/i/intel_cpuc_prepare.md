# Function: <code>intel_cpuc_prepare</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
```

```json
{
  "name": "intel_cpuc_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578900720,
      "name": "intel_cpuc_prepare",
      "external": true,
      "loc": "arch/x86/events/intel/core.c:3496",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578900720,
      "name": "intel_cpuc_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
```

```json
{
  "name": "intel_cpuc_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578902960,
      "name": "intel_cpuc_prepare",
      "external": true,
      "loc": "arch/x86/events/intel/core.c:3640",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578902960,
      "name": "intel_cpuc_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
```

```json
{
  "name": "intel_cpuc_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578904560,
      "name": "intel_cpuc_prepare",
      "external": true,
      "loc": "arch/x86/events/intel/core.c:3648",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578904560,
      "name": "intel_cpuc_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
```

```json
{
  "name": "intel_cpuc_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578909440,
      "name": "intel_cpuc_prepare",
      "external": true,
      "loc": "arch/x86/events/intel/core.c:3679",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578909440,
      "name": "intel_cpuc_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
```

```json
{
  "name": "intel_cpuc_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578907152,
      "name": "intel_cpuc_prepare",
      "external": true,
      "loc": "arch/x86/events/intel/core.c:4022",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578907152,
      "name": "intel_cpuc_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
```

```json
{
  "name": "intel_cpuc_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578911280,
      "name": "intel_cpuc_prepare",
      "external": true,
      "loc": "arch/x86/events/intel/core.c:4244",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578911280,
      "name": "intel_cpuc_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
```

```json
{
  "name": "intel_cpuc_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578914208,
      "name": "intel_cpuc_prepare",
      "external": true,
      "loc": "arch/x86/events/intel/core.c:4251",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578914208,
      "name": "intel_cpuc_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
```

```json
{
  "name": "intel_cpuc_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578920144,
      "name": "intel_cpuc_prepare",
      "external": true,
      "loc": "arch/x86/events/intel/core.c:4313",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578920144,
      "name": "intel_cpuc_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
```

```json
{
  "name": "intel_cpuc_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578936400,
      "name": "intel_cpuc_prepare",
      "external": true,
      "loc": "arch/x86/events/intel/core.c:4439",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578936400,
      "name": "intel_cpuc_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
```

```json
{
  "name": "intel_cpuc_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578934752,
      "name": "intel_cpuc_prepare",
      "external": true,
      "loc": "arch/x86/events/intel/core.c:4548",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578934752,
      "name": "intel_cpuc_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
```

```json
{
  "name": "intel_cpuc_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578957952,
      "name": "intel_cpuc_prepare",
      "external": true,
      "loc": "arch/x86/events/intel/core.c:4628",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578957952,
      "name": "intel_cpuc_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 695
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
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
```

```json
{
  "name": "intel_cpuc_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578904560,
      "name": "intel_cpuc_prepare",
      "external": true,
      "loc": "arch/x86/events/intel/core.c:3648",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578904560,
      "name": "intel_cpuc_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
```

```json
{
  "name": "intel_cpuc_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578899696,
      "name": "intel_cpuc_prepare",
      "external": true,
      "loc": "arch/x86/events/intel/core.c:3648",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578899696,
      "name": "intel_cpuc_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
```

```json
{
  "name": "intel_cpuc_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578904496,
      "name": "intel_cpuc_prepare",
      "external": true,
      "loc": "arch/x86/events/intel/core.c:3648",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578904496,
      "name": "intel_cpuc_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
```

```json
{
  "name": "intel_cpuc_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578904960,
      "name": "intel_cpuc_prepare",
      "external": true,
      "loc": "arch/x86/events/intel/core.c:3648",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:allocate_fake_cpuc",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578904960,
      "name": "intel_cpuc_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int intel_cpuc_prepare(struct cpu_hw_events * cpuc, int cpu)
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
