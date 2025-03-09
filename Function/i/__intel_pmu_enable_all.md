# Function: <code>__intel_pmu_enable_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __intel_pmu_enable_all(int added, bool pmi)
```

```json
{
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578889824,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:1527",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578889824,
      "name": "__intel_pmu_enable_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578894272,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:1757",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578894272,
      "name": "__intel_pmu_enable_all.constprop.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578894496,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:1757",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578894496,
      "name": "__intel_pmu_enable_all.constprop.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578893872,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:1892",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578893872,
      "name": "__intel_pmu_enable_all.constprop.18",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578895056,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:1892",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578895056,
      "name": "__intel_pmu_enable_all.constprop.19",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578896928,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:1892",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578896928,
      "name": "__intel_pmu_enable_all.constprop.19",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578897216,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:1896",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578897216,
      "name": "__intel_pmu_enable_all.constprop.25",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578899328,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:1966",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578899328,
      "name": "__intel_pmu_enable_all.constprop.0",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578900352,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:1967",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578900352,
      "name": "__intel_pmu_enable_all.constprop.0",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578903152,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:1974",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578903152,
      "name": "__intel_pmu_enable_all.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578899520,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:1998",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578899520,
      "name": "__intel_pmu_enable_all.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578903168,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2163",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578903168,
      "name": "__intel_pmu_enable_all.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578905136,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2165",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578905136,
      "name": "__intel_pmu_enable_all.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578909888,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2186",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:__intel_pmu_snapshot_branch_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578909888,
      "name": "__intel_pmu_enable_all.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578926320,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2196",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:__intel_pmu_snapshot_branch_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578926320,
      "name": "__intel_pmu_enable_all.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578924368,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2216",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:__intel_pmu_snapshot_branch_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578924368,
      "name": "__intel_pmu_enable_all.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578946528,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:2236",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:__intel_pmu_snapshot_branch_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578946528,
      "name": "__intel_pmu_enable_all.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578900352,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:1967",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578900352,
      "name": "__intel_pmu_enable_all.constprop.0",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578894608,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:1967",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578894608,
      "name": "__intel_pmu_enable_all.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578900288,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:1967",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578900288,
      "name": "__intel_pmu_enable_all.constprop.0",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__intel_pmu_enable_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578900752,
      "name": "__intel_pmu_enable_all",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:1967",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578900752,
      "name": "__intel_pmu_enable_all.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void __intel_pmu_enable_all(int added, bool pmi)
```
</details>
</li>
</ul>
