# Function: <code>rdt_get_cdp_config</code>

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
  "name": "rdt_get_cdp_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602826599,
      "name": "rdt_get_cdp_config",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:304",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init"
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
  "name": "rdt_get_cdp_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604633097,
      "name": "rdt_get_cdp_config",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:327",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
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
  "name": "rdt_get_cdp_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604730341,
      "name": "rdt_get_cdp_config",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:319",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
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
  "name": "rdt_get_cdp_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604743454,
      "name": "rdt_get_cdp_config",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:319",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
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
void rdt_get_cdp_config(int level, int type)
```

```json
{
  "name": "rdt_get_cdp_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579234719,
      "name": "rdt_get_cdp_config",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:319",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579234719,
      "name": "rdt_get_cdp_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void rdt_get_cdp_config(int level, int type)
```

```json
{
  "name": "rdt_get_cdp_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591256847,
      "name": "rdt_get_cdp_config",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:334",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591256847,
      "name": "rdt_get_cdp_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void rdt_get_cdp_config(int level, int type)
```

```json
{
  "name": "rdt_get_cdp_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591200435,
      "name": "rdt_get_cdp_config",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:334",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591200435,
      "name": "rdt_get_cdp_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
  "name": "rdt_get_cdp_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615219019,
      "name": "rdt_get_cdp_config",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:267",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources"
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
  "name": "rdt_get_cdp_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616992828,
      "name": "rdt_get_cdp_config",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:267",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources"
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
  "name": "rdt_get_cdp_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627618433,
      "name": "rdt_get_cdp_config",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:257",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources"
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
  "name": "rdt_get_cdp_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619373972,
      "name": "rdt_get_cdp_config",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:282",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources"
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
  "name": "rdt_get_cdp_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621669191,
      "name": "rdt_get_cdp_config",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:286",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources"
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
  "name": "rdt_get_cdp_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604669757,
      "name": "rdt_get_cdp_config",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:319",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
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
  "name": "rdt_get_cdp_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604637416,
      "name": "rdt_get_cdp_config",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:319",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
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
  "name": "rdt_get_cdp_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604747520,
      "name": "rdt_get_cdp_config",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:319",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
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
  "name": "rdt_get_cdp_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604747566,
      "name": "rdt_get_cdp_config",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:319",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
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
void rdt_get_cdp_config(int level, int type)
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
void rdt_get_cdp_config(int level, int type)
```
</details>
</li>
</ul>
