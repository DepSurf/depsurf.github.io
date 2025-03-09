# Function: <code>set_cpuid_faulting</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void set_cpuid_faulting(bool on)
```

```json
{
  "name": "set_cpuid_faulting",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579065424,
      "name": "set_cpuid_faulting",
      "external": false,
      "loc": "arch/x86/kernel/process.c:178",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:enable_cpuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579065424,
      "name": "set_cpuid_faulting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
  "name": "set_cpuid_faulting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579076682,
      "name": "set_cpuid_faulting",
      "external": false,
      "loc": "arch/x86/kernel/process.c:192",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:enable_cpuid"
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
  "name": "set_cpuid_faulting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579081977,
      "name": "set_cpuid_faulting",
      "external": false,
      "loc": "arch/x86/kernel/process.c:192",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:enable_cpuid"
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
  "name": "set_cpuid_faulting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579087433,
      "name": "set_cpuid_faulting",
      "external": false,
      "loc": "arch/x86/kernel/process.c:195",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:enable_cpuid"
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
  "name": "set_cpuid_faulting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579097129,
      "name": "set_cpuid_faulting",
      "external": false,
      "loc": "arch/x86/kernel/process.c:195",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:enable_cpuid"
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
  "name": "set_cpuid_faulting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579099113,
      "name": "set_cpuid_faulting",
      "external": false,
      "loc": "arch/x86/kernel/process.c:195",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:enable_cpuid"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpuid_faulting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579111609,
      "name": "set_cpuid_faulting",
      "external": false,
      "loc": "arch/x86/kernel/process.c:248",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:enable_cpuid"
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
  "name": "set_cpuid_faulting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579111449,
      "name": "set_cpuid_faulting",
      "external": false,
      "loc": "arch/x86/kernel/process.c:250",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:enable_cpuid"
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
  "name": "set_cpuid_faulting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579118089,
      "name": "set_cpuid_faulting",
      "external": false,
      "loc": "arch/x86/kernel/process.c:262",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:enable_cpuid"
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
  "name": "set_cpuid_faulting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579143545,
      "name": "set_cpuid_faulting",
      "external": false,
      "loc": "arch/x86/kernel/process.c:279",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:enable_cpuid"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_cpuid_faulting(bool on)
```

```json
{
  "name": "set_cpuid_faulting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579176278,
      "name": "set_cpuid_faulting",
      "external": false,
      "loc": "arch/x86/kernel/process.c:295",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579176112,
      "name": "set_cpuid_faulting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_cpuid_faulting(bool on)
```

```json
{
  "name": "set_cpuid_faulting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579230950,
      "name": "set_cpuid_faulting",
      "external": false,
      "loc": "arch/x86/kernel/process.c:295",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230768,
      "name": "set_cpuid_faulting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_cpuid_faulting(bool on)
```

```json
{
  "name": "set_cpuid_faulting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579236646,
      "name": "set_cpuid_faulting",
      "external": false,
      "loc": "arch/x86/kernel/process.c:321",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236464,
      "name": "set_cpuid_faulting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
  "name": "set_cpuid_faulting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579271561,
      "name": "set_cpuid_faulting",
      "external": false,
      "loc": "arch/x86/kernel/process.c:333",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:enable_cpuid"
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
  "name": "set_cpuid_faulting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579099497,
      "name": "set_cpuid_faulting",
      "external": false,
      "loc": "arch/x86/kernel/process.c:195",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:enable_cpuid"
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
  "name": "set_cpuid_faulting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579031933,
      "name": "set_cpuid_faulting",
      "external": false,
      "loc": "arch/x86/kernel/process.c:195",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:enable_cpuid"
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
  "name": "set_cpuid_faulting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579099049,
      "name": "set_cpuid_faulting",
      "external": false,
      "loc": "arch/x86/kernel/process.c:195",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:enable_cpuid"
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
  "name": "set_cpuid_faulting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579103520,
      "name": "set_cpuid_faulting",
      "external": false,
      "loc": "arch/x86/kernel/process.c:195",
      "file": "arch/x86/kernel/process.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:enable_cpuid"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void set_cpuid_faulting(bool on)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void set_cpuid_faulting(bool on)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void set_cpuid_faulting(bool on)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void set_cpuid_faulting(bool on)
```
</details>
</li>
</ul>
