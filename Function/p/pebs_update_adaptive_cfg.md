# Function: <code>pebs_update_adaptive_cfg</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pebs_update_adaptive_cfg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578907551,
      "name": "pebs_update_adaptive_cfg",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:959",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:pebs_update_state"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pebs_update_adaptive_cfg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578909290,
      "name": "pebs_update_adaptive_cfg",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:965",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:pebs_update_state"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
u64 pebs_update_adaptive_cfg(struct perf_event * event)
```

```json
{
  "name": "pebs_update_adaptive_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578913840,
      "name": "pebs_update_adaptive_cfg",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:966",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:pebs_update_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578913840,
      "name": "pebs_update_adaptive_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
u64 pebs_update_adaptive_cfg(struct perf_event * event)
```

```json
{
  "name": "pebs_update_adaptive_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578911120,
      "name": "pebs_update_adaptive_cfg",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:967",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:pebs_update_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578911120,
      "name": "pebs_update_adaptive_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pebs_update_adaptive_cfg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578916088,
      "name": "pebs_update_adaptive_cfg",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1065",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:pebs_update_state"
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
  "name": "pebs_update_adaptive_cfg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578919704,
      "name": "pebs_update_adaptive_cfg",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1066",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:pebs_update_state"
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
  "name": "pebs_update_adaptive_cfg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578926323,
      "name": "pebs_update_adaptive_cfg",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1115",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:pebs_update_state"
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
  "name": "pebs_update_adaptive_cfg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578942814,
      "name": "pebs_update_adaptive_cfg",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1132",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:pebs_update_state"
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
  "name": "pebs_update_adaptive_cfg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578940968,
      "name": "pebs_update_adaptive_cfg",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1181",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:pebs_update_state"
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
  "name": "pebs_update_adaptive_cfg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578964328,
      "name": "pebs_update_adaptive_cfg",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:1186",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:pebs_update_state"
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
  "name": "pebs_update_adaptive_cfg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578909290,
      "name": "pebs_update_adaptive_cfg",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:965",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:pebs_update_state"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pebs_update_adaptive_cfg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578904522,
      "name": "pebs_update_adaptive_cfg",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:965",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:pebs_update_state"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pebs_update_adaptive_cfg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578909226,
      "name": "pebs_update_adaptive_cfg",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:965",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:pebs_update_state"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pebs_update_adaptive_cfg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578909754,
      "name": "pebs_update_adaptive_cfg",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:965",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:pebs_update_state"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
u64 pebs_update_adaptive_cfg(struct perf_event * event)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
u64 pebs_update_adaptive_cfg(struct perf_event * event)
```
</details>
</li>
</ul>
