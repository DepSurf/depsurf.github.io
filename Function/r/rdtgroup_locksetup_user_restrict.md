# Function: <code>rdtgroup_locksetup_user_restrict</code>

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
  "name": "rdtgroup_locksetup_user_restrict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579226274,
      "name": "rdtgroup_locksetup_user_restrict",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:559",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
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
  "name": "rdtgroup_locksetup_user_restrict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579239460,
      "name": "rdtgroup_locksetup_user_restrict",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:548",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
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
  "name": "rdtgroup_locksetup_user_restrict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579241684,
      "name": "rdtgroup_locksetup_user_restrict",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:548",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
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
int rdtgroup_locksetup_user_restrict(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_locksetup_user_restrict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579260656,
      "name": "rdtgroup_locksetup_user_restrict",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:548",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579260656,
      "name": "rdtgroup_locksetup_user_restrict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
int rdtgroup_locksetup_user_restrict(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_locksetup_user_restrict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579253152,
      "name": "rdtgroup_locksetup_user_restrict",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:548",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579253152,
      "name": "rdtgroup_locksetup_user_restrict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
  "name": "rdtgroup_locksetup_user_restrict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579259237,
      "name": "rdtgroup_locksetup_user_restrict",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:548",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
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
  "name": "rdtgroup_locksetup_user_restrict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579300381,
      "name": "rdtgroup_locksetup_user_restrict",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:552",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
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
  "name": "rdtgroup_locksetup_user_restrict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579355771,
      "name": "rdtgroup_locksetup_user_restrict",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:552",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
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
  "name": "rdtgroup_locksetup_user_restrict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579426251,
      "name": "rdtgroup_locksetup_user_restrict",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:554",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
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
  "name": "rdtgroup_locksetup_user_restrict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579438162,
      "name": "rdtgroup_locksetup_user_restrict",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:554",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
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
  "name": "rdtgroup_locksetup_user_restrict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579467746,
      "name": "rdtgroup_locksetup_user_restrict",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:568",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
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
  "name": "rdtgroup_locksetup_user_restrict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579240532,
      "name": "rdtgroup_locksetup_user_restrict",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:548",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
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
  "name": "rdtgroup_locksetup_user_restrict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579176116,
      "name": "rdtgroup_locksetup_user_restrict",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:548",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
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
  "name": "rdtgroup_locksetup_user_restrict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579241604,
      "name": "rdtgroup_locksetup_user_restrict",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:548",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
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
  "name": "rdtgroup_locksetup_user_restrict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579247172,
      "name": "rdtgroup_locksetup_user_restrict",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:548",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
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
int rdtgroup_locksetup_user_restrict(struct rdtgroup * rdtgrp)
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
int rdtgroup_locksetup_user_restrict(struct rdtgroup * rdtgrp)
```
</details>
</li>
</ul>
