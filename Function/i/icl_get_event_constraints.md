# Function: <code>icl_get_event_constraints</code>

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
struct event_constraint * icl_get_event_constraints(struct cpu_hw_events * cpuc, int idx, struct perf_event * event)
```

```json
{
  "name": "icl_get_event_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578898704,
      "name": "icl_get_event_constraints",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3477",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578898704,
      "name": "icl_get_event_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
struct event_constraint * icl_get_event_constraints(struct cpu_hw_events * cpuc, int idx, struct perf_event * event)
```

```json
{
  "name": "icl_get_event_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578899840,
      "name": "icl_get_event_constraints",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3485",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578899840,
      "name": "icl_get_event_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
struct event_constraint * icl_get_event_constraints(struct cpu_hw_events * cpuc, int idx, struct perf_event * event)
```

```json
{
  "name": "icl_get_event_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578904912,
      "name": "icl_get_event_constraints",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3516",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578904912,
      "name": "icl_get_event_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
struct event_constraint * icl_get_event_constraints(struct cpu_hw_events * cpuc, int idx, struct perf_event * event)
```

```json
{
  "name": "icl_get_event_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578901872,
      "name": "icl_get_event_constraints",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3859",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578901872,
      "name": "icl_get_event_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct event_constraint * icl_get_event_constraints(struct cpu_hw_events * cpuc, int idx, struct perf_event * event)
```

```json
{
  "name": "icl_get_event_constraints",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578910949,
      "name": "icl_get_event_constraints",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4015",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:spr_get_event_constraints"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578910704,
      "name": "icl_get_event_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct event_constraint * icl_get_event_constraints(struct cpu_hw_events * cpuc, int idx, struct perf_event * event)
```

```json
{
  "name": "icl_get_event_constraints",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578913877,
      "name": "icl_get_event_constraints",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4022",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:spr_get_event_constraints"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578913536,
      "name": "icl_get_event_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct event_constraint * icl_get_event_constraints(struct cpu_hw_events * cpuc, int idx, struct perf_event * event)
```

```json
{
  "name": "icl_get_event_constraints",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578919749,
      "name": "icl_get_event_constraints",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4084",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:spr_get_event_constraints"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578919376,
      "name": "icl_get_event_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct event_constraint * icl_get_event_constraints(struct cpu_hw_events * cpuc, int idx, struct perf_event * event)
```

```json
{
  "name": "icl_get_event_constraints",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578935973,
      "name": "icl_get_event_constraints",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4213",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:spr_get_event_constraints"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578935568,
      "name": "icl_get_event_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct event_constraint * icl_get_event_constraints(struct cpu_hw_events * cpuc, int idx, struct perf_event * event)
```

```json
{
  "name": "icl_get_event_constraints",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578934053,
      "name": "icl_get_event_constraints",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4250",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:spr_get_event_constraints"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578933648,
      "name": "icl_get_event_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct event_constraint * icl_get_event_constraints(struct cpu_hw_events * cpuc, int idx, struct perf_event * event)
```

```json
{
  "name": "icl_get_event_constraints",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578957317,
      "name": "icl_get_event_constraints",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4325",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:glc_get_event_constraints"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578956912,
      "name": "icl_get_event_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
struct event_constraint * icl_get_event_constraints(struct cpu_hw_events * cpuc, int idx, struct perf_event * event)
```

```json
{
  "name": "icl_get_event_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578899840,
      "name": "icl_get_event_constraints",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3485",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578899840,
      "name": "icl_get_event_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
struct event_constraint * icl_get_event_constraints(struct cpu_hw_events * cpuc, int idx, struct perf_event * event)
```

```json
{
  "name": "icl_get_event_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578893696,
      "name": "icl_get_event_constraints",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3485",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578893696,
      "name": "icl_get_event_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
struct event_constraint * icl_get_event_constraints(struct cpu_hw_events * cpuc, int idx, struct perf_event * event)
```

```json
{
  "name": "icl_get_event_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578899776,
      "name": "icl_get_event_constraints",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3485",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578899776,
      "name": "icl_get_event_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
struct event_constraint * icl_get_event_constraints(struct cpu_hw_events * cpuc, int idx, struct perf_event * event)
```

```json
{
  "name": "icl_get_event_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578900336,
      "name": "icl_get_event_constraints",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3485",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578900336,
      "name": "icl_get_event_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
struct event_constraint * icl_get_event_constraints(struct cpu_hw_events * cpuc, int idx, struct perf_event * event)
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
struct event_constraint * icl_get_event_constraints(struct cpu_hw_events * cpuc, int idx, struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct event_constraint * icl_get_event_constraints(struct cpu_hw_events * cpuc, int idx, struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct event_constraint * icl_get_event_constraints(struct cpu_hw_events * cpuc, int idx, struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct event_constraint * icl_get_event_constraints(struct cpu_hw_events * cpuc, int idx, struct perf_event * event)
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
