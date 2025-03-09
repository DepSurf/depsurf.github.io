# Function: <code>clear_APIC_ibs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578883824,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:872",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend",
        "arch/x86/events/amd/ibs.c:perf_ibs_cpu_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578883824,
      "name": "clear_APIC_ibs.isra.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void clear_APIC_ibs()
```

```json
{
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578882960,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:939",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578882960,
      "name": "clear_APIC_ibs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void clear_APIC_ibs()
```

```json
{
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578883024,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:939",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578883024,
      "name": "clear_APIC_ibs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void clear_APIC_ibs()
```

```json
{
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578882224,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:940",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578882224,
      "name": "clear_APIC_ibs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void clear_APIC_ibs()
```

```json
{
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578883296,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:940",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578883296,
      "name": "clear_APIC_ibs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void clear_APIC_ibs()
```

```json
{
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578885088,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:944",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578885088,
      "name": "clear_APIC_ibs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void clear_APIC_ibs()
```

```json
{
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578884880,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:944",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578884880,
      "name": "clear_APIC_ibs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void clear_APIC_ibs()
```

```json
{
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578886112,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:940",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578886112,
      "name": "clear_APIC_ibs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void clear_APIC_ibs()
```

```json
{
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578887120,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:942",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578887120,
      "name": "clear_APIC_ibs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578892101,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:942",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
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
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578887493,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:985",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
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
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578889765,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:985",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
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
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578891685,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:989",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
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
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578894389,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:1134",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
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
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578906757,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:1460",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
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
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578904165,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:1456",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
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
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578925877,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:1465",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void clear_APIC_ibs()
```

```json
{
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578887120,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:942",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578887120,
      "name": "clear_APIC_ibs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void clear_APIC_ibs()
```

```json
{
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578881232,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:942",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578881232,
      "name": "clear_APIC_ibs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void clear_APIC_ibs()
```

```json
{
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578887056,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:942",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578887056,
      "name": "clear_APIC_ibs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void clear_APIC_ibs()
```

```json
{
  "name": "clear_APIC_ibs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578887408,
      "name": "clear_APIC_ibs",
      "external": false,
      "loc": "arch/x86/events/amd/ibs.c:942",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578887408,
      "name": "clear_APIC_ibs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void clear_APIC_ibs()
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void clear_APIC_ibs()
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void clear_APIC_ibs()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void clear_APIC_ibs()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void clear_APIC_ibs()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void clear_APIC_ibs()
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
