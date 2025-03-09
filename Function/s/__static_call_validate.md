# Function: <code>__static_call_validate</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __static_call_validate(void * insn, bool tail)
```

```json
{
  "name": "__static_call_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579106608,
      "name": "__static_call_validate",
      "external": false,
      "loc": "arch/x86/kernel/static_call.c:47",
      "file": "arch/x86/kernel/static_call.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/static_call.c:arch_static_call_transform",
        "arch/x86/kernel/static_call.c:arch_static_call_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579106608,
      "name": "__static_call_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void __static_call_validate(void * insn, bool tail)
```

```json
{
  "name": "__static_call_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579113152,
      "name": "__static_call_validate",
      "external": false,
      "loc": "arch/x86/kernel/static_call.c:59",
      "file": "arch/x86/kernel/static_call.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/static_call.c:arch_static_call_transform",
        "arch/x86/kernel/static_call.c:arch_static_call_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579113152,
      "name": "__static_call_validate",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __static_call_validate(void * insn, bool tail)
```

```json
{
  "name": "__static_call_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__static_call_validate",
      "external": false,
      "loc": "arch/x86/kernel/static_call.c:59",
      "file": "arch/x86/kernel/static_call.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/static_call.c:arch_static_call_transform",
        "arch/x86/kernel/static_call.c:arch_static_call_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579138384,
      "name": "__static_call_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071592058043,
      "name": "__static_call_validate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __static_call_validate(void * insn, bool tail, bool tramp)
```

```json
{
  "name": "__static_call_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__static_call_validate",
      "external": false,
      "loc": "arch/x86/kernel/static_call.c:70",
      "file": "arch/x86/kernel/static_call.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/static_call.c:arch_static_call_transform",
        "arch/x86/kernel/static_call.c:arch_static_call_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579175168,
      "name": "__static_call_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071593826270,
      "name": "__static_call_validate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void __static_call_validate(u8 * insn, bool tail, bool tramp)
```

```json
{
  "name": "__static_call_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579229456,
      "name": "__static_call_validate",
      "external": false,
      "loc": "arch/x86/kernel/static_call.c:114",
      "file": "arch/x86/kernel/static_call.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/static_call.c:arch_static_call_transform",
        "arch/x86/kernel/static_call.c:arch_static_call_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229456,
      "name": "__static_call_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void __static_call_validate(u8 * insn, bool tail, bool tramp)
```

```json
{
  "name": "__static_call_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579235248,
      "name": "__static_call_validate",
      "external": false,
      "loc": "arch/x86/kernel/static_call.c:114",
      "file": "arch/x86/kernel/static_call.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/static_call.c:arch_static_call_transform",
        "arch/x86/kernel/static_call.c:arch_static_call_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579235248,
      "name": "__static_call_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void __static_call_validate(u8 * insn, bool tail, bool tramp)
```

```json
{
  "name": "__static_call_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579264096,
      "name": "__static_call_validate",
      "external": false,
      "loc": "arch/x86/kernel/static_call.c:114",
      "file": "arch/x86/kernel/static_call.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/static_call.c:arch_static_call_transform",
        "arch/x86/kernel/static_call.c:arch_static_call_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579264096,
      "name": "__static_call_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void __static_call_validate(void * insn, bool tail)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool tramp</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void * insn</code> ➡️ <code>u8 * insn</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
