# Function: <code>uncore_event_to_box</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_box * uncore_event_to_box(struct perf_event * event)
```

```json
{
  "name": "uncore_event_to_box",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578936928,
      "name": "uncore_event_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:115",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_read",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_del",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_add",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_stop",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_del",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_start",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578936928,
      "name": "uncore_event_to_box",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_box",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:334",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:334",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_box",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:339",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:339",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_box",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:339",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:339",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_box",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:340",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:340",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:461",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:478",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:500",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:488",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578949989,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:491",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_read",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_del",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_add",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578951637,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:528",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_read",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_del",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_add",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578956629,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:541",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_read",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_del",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_add",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578967237,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:542",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_read",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_del",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_add",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start"
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
  "name": "uncore_event_to_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578978149,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:542",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_read",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_del",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_add",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578996917,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:558",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_read",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_del",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_add",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start"
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
  "name": "uncore_event_to_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578996645,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:561",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_read",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_del",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_add",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start"
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
  "name": "uncore_event_to_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579021573,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:561",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_read",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_del",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_add",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:488",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:488",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:488",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:488",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
struct intel_uncore_box * uncore_event_to_box(struct perf_event * event)
```
</details>
</li>
</ul>
