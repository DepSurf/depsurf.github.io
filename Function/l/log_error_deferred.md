# Function: <code>log_error_deferred</code>

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
  "name": "log_error_deferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579150059,
      "name": "log_error_deferred",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:832",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt"
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
  "name": "log_error_deferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579164971,
      "name": "log_error_deferred",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:817",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt"
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
  "name": "log_error_deferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579175858,
      "name": "log_error_deferred",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce_amd.c:869",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt"
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
  "name": "log_error_deferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579165215,
      "name": "log_error_deferred",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:869",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
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
  "name": "log_error_deferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579177133,
      "name": "log_error_deferred",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:949",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
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
  "name": "log_error_deferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579179533,
      "name": "log_error_deferred",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:951",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
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
void log_error_deferred(unsigned int bank)
```

```json
{
  "name": "log_error_deferred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579199168,
      "name": "log_error_deferred",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:964",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579199168,
      "name": "log_error_deferred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
void log_error_deferred(unsigned int bank)
```

```json
{
  "name": "log_error_deferred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579194848,
      "name": "log_error_deferred",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:964",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579194848,
      "name": "log_error_deferred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
  "name": "log_error_deferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579199391,
      "name": "log_error_deferred",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:964",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
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
  "name": "log_error_deferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579235263,
      "name": "log_error_deferred",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:977",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
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
  "name": "log_error_deferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579286640,
      "name": "log_error_deferred",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:800",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
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
  "name": "log_error_deferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579352211,
      "name": "log_error_deferred",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:818",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
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
  "name": "log_error_deferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579361171,
      "name": "log_error_deferred",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:814",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
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
  "name": "log_error_deferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579391043,
      "name": "log_error_deferred",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:864",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
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
  "name": "log_error_deferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579179789,
      "name": "log_error_deferred",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:951",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
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
  "name": "log_error_deferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579112198,
      "name": "log_error_deferred",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:951",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
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
  "name": "log_error_deferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579179453,
      "name": "log_error_deferred",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:951",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
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
  "name": "log_error_deferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579184637,
      "name": "log_error_deferred",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/amd.c:951",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
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
void log_error_deferred(unsigned int bank)
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
void log_error_deferred(unsigned int bank)
```
</details>
</li>
</ul>
