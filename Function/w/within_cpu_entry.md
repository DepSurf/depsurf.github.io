# Function: <code>within_cpu_entry</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "within_cpu_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579098923,
      "name": "within_cpu_entry",
      "external": false,
      "loc": "arch/x86/kernel/hw_breakpoint.c:263",
      "file": "arch/x86/kernel/hw_breakpoint.c",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "within_cpu_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579099055,
      "name": "within_cpu_entry",
      "external": false,
      "loc": "arch/x86/kernel/hw_breakpoint.c:263",
      "file": "arch/x86/kernel/hw_breakpoint.c",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "within_cpu_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579105526,
      "name": "within_cpu_entry",
      "external": false,
      "loc": "arch/x86/kernel/hw_breakpoint.c:263",
      "file": "arch/x86/kernel/hw_breakpoint.c",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "within_cpu_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579129615,
      "name": "within_cpu_entry",
      "external": false,
      "loc": "arch/x86/kernel/hw_breakpoint.c:263",
      "file": "arch/x86/kernel/hw_breakpoint.c",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "within_cpu_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579165342,
      "name": "within_cpu_entry",
      "external": false,
      "loc": "arch/x86/kernel/hw_breakpoint.c:263",
      "file": "arch/x86/kernel/hw_breakpoint.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool within_cpu_entry(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "within_cpu_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579218224,
      "name": "within_cpu_entry",
      "external": false,
      "loc": "arch/x86/kernel/hw_breakpoint.c:263",
      "file": "arch/x86/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579218224,
      "name": "within_cpu_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
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
bool within_cpu_entry(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "within_cpu_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579223664,
      "name": "within_cpu_entry",
      "external": false,
      "loc": "arch/x86/kernel/hw_breakpoint.c:263",
      "file": "arch/x86/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223664,
      "name": "within_cpu_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
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
bool within_cpu_entry(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "within_cpu_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579252528,
      "name": "within_cpu_entry",
      "external": false,
      "loc": "arch/x86/kernel/hw_breakpoint.c:263",
      "file": "arch/x86/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579252528,
      "name": "within_cpu_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool within_cpu_entry(long unsigned int addr, long unsigned int end)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
