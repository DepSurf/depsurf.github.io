# Function: <code>fixed_counter_disabled</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool fixed_counter_disabled(int i, struct pmu * pmu)
```

```json
{
  "name": "fixed_counter_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578873374,
      "name": "fixed_counter_disabled",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1195",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_event_print_debug"
      ]
    },
    {
      "addr": 18446744071578907596,
      "name": "fixed_counter_disabled",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1195",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591181358,
      "name": "fixed_counter_disabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool fixed_counter_disabled(int i, struct pmu * pmu)
```

```json
{
  "name": "fixed_counter_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578875448,
      "name": "fixed_counter_disabled",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1195",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_event_print_debug"
      ]
    },
    {
      "addr": 18446744071578911126,
      "name": "fixed_counter_disabled",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1195",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592037515,
      "name": "fixed_counter_disabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool fixed_counter_disabled(int i, struct pmu * pmu)
```

```json
{
  "name": "fixed_counter_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578872706,
      "name": "fixed_counter_disabled",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1221",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_event_print_debug"
      ]
    },
    {
      "addr": 18446744071578916780,
      "name": "fixed_counter_disabled",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1221",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593803605,
      "name": "fixed_counter_disabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fixed_counter_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578885740,
      "name": "fixed_counter_disabled",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1291",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578931652,
      "name": "fixed_counter_disabled",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1291",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_reset"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fixed_counter_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578883714,
      "name": "fixed_counter_disabled",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1296",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578929703,
      "name": "fixed_counter_disabled",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1296",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_reset"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fixed_counter_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578906018,
      "name": "fixed_counter_disabled",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1311",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578950167,
      "name": "fixed_counter_disabled",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1311",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
bool fixed_counter_disabled(int i, struct pmu * pmu)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool fixed_counter_disabled(int i, struct pmu * pmu)
```
</details>
</li>
</ul>
