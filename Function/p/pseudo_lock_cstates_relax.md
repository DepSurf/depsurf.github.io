# Function: <code>pseudo_lock_cstates_relax</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void pseudo_lock_cstates_relax(struct pseudo_lock_region * plr)
```

```json
{
  "name": "pseudo_lock_cstates_relax",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579222352,
      "name": "pseudo_lock_cstates_relax",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:181",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579222352,
      "name": "pseudo_lock_cstates_relax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void pseudo_lock_cstates_relax(struct pseudo_lock_region * plr)
```

```json
{
  "name": "pseudo_lock_cstates_relax",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579235488,
      "name": "pseudo_lock_cstates_relax",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:174",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579235488,
      "name": "pseudo_lock_cstates_relax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void pseudo_lock_cstates_relax(struct pseudo_lock_region * plr)
```

```json
{
  "name": "pseudo_lock_cstates_relax",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579237760,
      "name": "pseudo_lock_cstates_relax",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:174",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579237760,
      "name": "pseudo_lock_cstates_relax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
  "name": "pseudo_lock_cstates_relax",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579267429,
      "name": "pseudo_lock_cstates_relax",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:174",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_cstates_constrain"
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
  "name": "pseudo_lock_cstates_relax",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579259797,
      "name": "pseudo_lock_cstates_relax",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:174",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_cstates_constrain"
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
  "name": "pseudo_lock_cstates_relax",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579261537,
      "name": "pseudo_lock_cstates_relax",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:174",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
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
  "name": "pseudo_lock_cstates_relax",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579302785,
      "name": "pseudo_lock_cstates_relax",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:175",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
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
  "name": "pseudo_lock_cstates_relax",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579358225,
      "name": "pseudo_lock_cstates_relax",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:175",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
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
  "name": "pseudo_lock_cstates_relax",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579429137,
      "name": "pseudo_lock_cstates_relax",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:175",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
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
  "name": "pseudo_lock_cstates_relax",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579441105,
      "name": "pseudo_lock_cstates_relax",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:175",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
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
  "name": "pseudo_lock_cstates_relax",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579470753,
      "name": "pseudo_lock_cstates_relax",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:189",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
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
void pseudo_lock_cstates_relax(struct pseudo_lock_region * plr)
```

```json
{
  "name": "pseudo_lock_cstates_relax",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579236608,
      "name": "pseudo_lock_cstates_relax",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:174",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236608,
      "name": "pseudo_lock_cstates_relax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void pseudo_lock_cstates_relax(struct pseudo_lock_region * plr)
```

```json
{
  "name": "pseudo_lock_cstates_relax",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579171888,
      "name": "pseudo_lock_cstates_relax",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:174",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579171888,
      "name": "pseudo_lock_cstates_relax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void pseudo_lock_cstates_relax(struct pseudo_lock_region * plr)
```

```json
{
  "name": "pseudo_lock_cstates_relax",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579237680,
      "name": "pseudo_lock_cstates_relax",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:174",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579237680,
      "name": "pseudo_lock_cstates_relax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void pseudo_lock_cstates_relax(struct pseudo_lock_region * plr)
```

```json
{
  "name": "pseudo_lock_cstates_relax",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579243152,
      "name": "pseudo_lock_cstates_relax",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:174",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579243152,
      "name": "pseudo_lock_cstates_relax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void pseudo_lock_cstates_relax(struct pseudo_lock_region * plr)
```
</details>
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
void pseudo_lock_cstates_relax(struct pseudo_lock_region * plr)
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
void pseudo_lock_cstates_relax(struct pseudo_lock_region * plr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void pseudo_lock_cstates_relax(struct pseudo_lock_region * plr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void pseudo_lock_cstates_relax(struct pseudo_lock_region * plr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void pseudo_lock_cstates_relax(struct pseudo_lock_region * plr)
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
