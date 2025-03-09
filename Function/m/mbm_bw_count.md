# Function: <code>mbm_bw_count</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mbm_bw_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579148389,
      "name": "mbm_bw_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:282",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mbm_bw_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579214821,
      "name": "mbm_bw_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:279",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mbm_bw_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579227863,
      "name": "mbm_bw_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:271",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update"
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
  "name": "mbm_bw_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579230087,
      "name": "mbm_bw_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:271",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update"
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
void mbm_bw_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "mbm_bw_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579253520,
      "name": "mbm_bw_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:271",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579253520,
      "name": "mbm_bw_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void mbm_bw_count(u32 rmid, struct rmid_read * rr)
```

```json
{
  "name": "mbm_bw_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579246384,
      "name": "mbm_bw_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:335",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579246384,
      "name": "mbm_bw_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
  "name": "mbm_bw_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579248500,
      "name": "mbm_bw_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:328",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mbm_bw_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579289084,
      "name": "mbm_bw_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:335",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mbm_bw_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579343356,
      "name": "mbm_bw_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:335",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mbm_bw_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579413020,
      "name": "mbm_bw_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:420",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mbm_bw_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579425468,
      "name": "mbm_bw_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:432",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mbm_bw_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579455052,
      "name": "mbm_bw_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:432",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
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
  "name": "mbm_bw_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579228935,
      "name": "mbm_bw_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:271",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update"
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
  "name": "mbm_bw_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579163915,
      "name": "mbm_bw_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:271",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update"
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
  "name": "mbm_bw_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579230007,
      "name": "mbm_bw_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:271",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update"
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
  "name": "mbm_bw_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579235415,
      "name": "mbm_bw_count",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:271",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update"
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
void mbm_bw_count(u32 rmid, struct rmid_read * rr)
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
void mbm_bw_count(u32 rmid, struct rmid_read * rr)
```
</details>
</li>
</ul>
