# Function: <code>dyn_constraint</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dyn_constraint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578894528,
      "name": "dyn_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2805",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:tfa_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578894528,
      "name": "dyn_constraint.isra.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dyn_constraint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578896480,
      "name": "dyn_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2886",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:tfa_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578896480,
      "name": "dyn_constraint.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dyn_constraint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578897552,
      "name": "dyn_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2887",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:tfa_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578897552,
      "name": "dyn_constraint.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
struct event_constraint * dyn_constraint(struct cpu_hw_events * cpuc, struct event_constraint * c, int idx)
```

```json
{
  "name": "dyn_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578898816,
      "name": "dyn_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2906",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:tfa_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578898816,
      "name": "dyn_constraint",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct event_constraint * dyn_constraint(struct cpu_hw_events * cpuc, struct event_constraint * c, int idx)
```

```json
{
  "name": "dyn_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578894656,
      "name": "dyn_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3193",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:tfa_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578894656,
      "name": "dyn_constraint",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct event_constraint * dyn_constraint(struct cpu_hw_events * cpuc, struct event_constraint * c, int idx)
```

```json
{
  "name": "dyn_constraint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578896576,
      "name": "dyn_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3303",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:tfa_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578896576,
      "name": "dyn_constraint",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dyn_constraint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578913766,
      "name": "dyn_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3310",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:tfa_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
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
  "name": "dyn_constraint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578919621,
      "name": "dyn_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3372",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:tfa_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
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
  "name": "dyn_constraint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578935829,
      "name": "dyn_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3445",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:tfa_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_get_excl_constraints"
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
  "name": "dyn_constraint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578933909,
      "name": "dyn_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3463",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:tfa_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_get_excl_constraints"
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
  "name": "dyn_constraint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578957173,
      "name": "dyn_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:3471",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:tfa_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_get_excl_constraints"
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
  "name": "dyn_constraint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578897552,
      "name": "dyn_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2887",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:tfa_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578897552,
      "name": "dyn_constraint.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dyn_constraint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578891408,
      "name": "dyn_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2887",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:tfa_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578891408,
      "name": "dyn_constraint.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dyn_constraint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578897488,
      "name": "dyn_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2887",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:tfa_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578897488,
      "name": "dyn_constraint.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dyn_constraint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578898048,
      "name": "dyn_constraint",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2887",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:tfa_get_event_constraints",
        "arch/x86/events/intel/core.c:intel_get_event_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578898048,
      "name": "dyn_constraint.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct event_constraint * dyn_constraint(struct cpu_hw_events * cpuc, struct event_constraint * c, int idx)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
struct event_constraint * dyn_constraint(struct cpu_hw_events * cpuc, struct event_constraint * c, int idx)
```
</details>
</li>
</ul>
