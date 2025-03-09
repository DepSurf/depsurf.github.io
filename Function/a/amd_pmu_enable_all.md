# Function: <code>amd_pmu_enable_all</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void amd_pmu_enable_all(int added)
```

```json
{
  "name": "amd_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578886032,
      "name": "amd_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:771",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_disable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_enable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_enable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578886032,
      "name": "amd_pmu_enable_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void amd_pmu_enable_all(int added)
```

```json
{
  "name": "amd_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578892928,
      "name": "amd_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:721",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_disable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_enable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_enable_virt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578892928,
      "name": "amd_pmu_enable_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void amd_pmu_enable_all(int added)
```

```json
{
  "name": "amd_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578891136,
      "name": "amd_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:721",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_disable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_enable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_enable_virt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578891136,
      "name": "amd_pmu_enable_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void amd_pmu_enable_all(int added)
```

```json
{
  "name": "amd_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578913536,
      "name": "amd_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/amd/core.c:723",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_disable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_enable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_enable_virt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578913536,
      "name": "amd_pmu_enable_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void amd_pmu_enable_all(int added)
```
</details>
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
