# Function: <code>init_intel_misc_features</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_intel_misc_features",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579106854,
      "name": "init_intel_misc_features",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:497",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_intel_misc_features",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579120027,
      "name": "init_intel_misc_features",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:552",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_intel_misc_features",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579127739,
      "name": "init_intel_misc_features",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:631",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
  "name": "init_intel_misc_features",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579134413,
      "name": "init_intel_misc_features",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:639",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
  "name": "init_intel_misc_features",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579145160,
      "name": "init_intel_misc_features",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:636",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
  "name": "init_intel_misc_features",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579147420,
      "name": "init_intel_misc_features",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:637",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
void init_intel_misc_features(struct cpuinfo_x86 * c)
```

```json
{
  "name": "init_intel_misc_features",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579164176,
      "name": "init_intel_misc_features",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:585",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579164176,
      "name": "init_intel_misc_features",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
void init_intel_misc_features(struct cpuinfo_x86 * c)
```

```json
{
  "name": "init_intel_misc_features",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579161408,
      "name": "init_intel_misc_features",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:586",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579161408,
      "name": "init_intel_misc_features",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
  "name": "init_intel_misc_features",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579169685,
      "name": "init_intel_misc_features",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:587",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
  "name": "init_intel_misc_features",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579202807,
      "name": "init_intel_misc_features",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:589",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
  "name": "init_intel_misc_features",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579252842,
      "name": "init_intel_misc_features",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:624",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
  "name": "init_intel_misc_features",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579314538,
      "name": "init_intel_misc_features",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:766",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
  "name": "init_intel_misc_features",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579321690,
      "name": "init_intel_misc_features",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:766",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
  "name": "init_intel_misc_features",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579351597,
      "name": "init_intel_misc_features",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:586",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
  "name": "init_intel_misc_features",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579147788,
      "name": "init_intel_misc_features",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:637",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
  "name": "init_intel_misc_features",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579079014,
      "name": "init_intel_misc_features",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:637",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
  "name": "init_intel_misc_features",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579147340,
      "name": "init_intel_misc_features",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:637",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
  "name": "init_intel_misc_features",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579152476,
      "name": "init_intel_misc_features",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:637",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
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
void init_intel_misc_features(struct cpuinfo_x86 * c)
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
void init_intel_misc_features(struct cpuinfo_x86 * c)
```
</details>
</li>
</ul>
