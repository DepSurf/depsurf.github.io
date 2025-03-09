# Function: <code>pseudo_lock_region_init</code>

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
  "name": "pseudo_lock_region_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579227285,
      "name": "pseudo_lock_region_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:282",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pseudo_lock_region_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579240485,
      "name": "pseudo_lock_region_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:275",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pseudo_lock_region_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579242709,
      "name": "pseudo_lock_region_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:275",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int pseudo_lock_region_init(struct pseudo_lock_region * plr)
```

```json
{
  "name": "pseudo_lock_region_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579262960,
      "name": "pseudo_lock_region_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:275",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262960,
      "name": "pseudo_lock_region_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
int pseudo_lock_region_init(struct pseudo_lock_region * plr)
```

```json
{
  "name": "pseudo_lock_region_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579255456,
      "name": "pseudo_lock_region_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:275",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255456,
      "name": "pseudo_lock_region_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
  "name": "pseudo_lock_region_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579257141,
      "name": "pseudo_lock_region_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:275",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc"
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
  "name": "pseudo_lock_region_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579298277,
      "name": "pseudo_lock_region_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:279",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc"
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
  "name": "pseudo_lock_region_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579353429,
      "name": "pseudo_lock_region_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:279",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc"
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
  "name": "pseudo_lock_region_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579427542,
      "name": "pseudo_lock_region_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:279",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "pseudo_lock_region_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579439494,
      "name": "pseudo_lock_region_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:279",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "pseudo_lock_region_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579469126,
      "name": "pseudo_lock_region_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:293",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pseudo_lock_region_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579241557,
      "name": "pseudo_lock_region_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:275",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pseudo_lock_region_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579177141,
      "name": "pseudo_lock_region_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:275",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pseudo_lock_region_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579242629,
      "name": "pseudo_lock_region_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:275",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pseudo_lock_region_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579248197,
      "name": "pseudo_lock_region_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:275",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int pseudo_lock_region_init(struct pseudo_lock_region * plr)
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
int pseudo_lock_region_init(struct pseudo_lock_region * plr)
```
</details>
</li>
</ul>
