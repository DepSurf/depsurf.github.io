# Function: <code>__static_call_transform</code>

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
void __static_call_transform(void * insn, enum insn_type type, void * func)
```

```json
{
  "name": "__static_call_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591662640,
      "name": "__static_call_transform",
      "external": false,
      "loc": "arch/x86/kernel/static_call.c:14",
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
      "addr": 18446744071591662640,
      "name": "__static_call_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
void __static_call_transform(void * insn, enum insn_type type, void * func)
```

```json
{
  "name": "__static_call_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591606400,
      "name": "__static_call_transform",
      "external": false,
      "loc": "arch/x86/kernel/static_call.c:20",
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
      "addr": 18446744071591606400,
      "name": "__static_call_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __static_call_transform(void * insn, enum insn_type type, void * func)
```

```json
{
  "name": "__static_call_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592779632,
      "name": "__static_call_transform",
      "external": false,
      "loc": "arch/x86/kernel/static_call.c:20",
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
      "addr": 18446744071592779632,
      "name": "__static_call_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __static_call_transform(void * insn, enum insn_type type, void * func, bool modinit)
```

```json
{
  "name": "__static_call_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594677536,
      "name": "__static_call_transform",
      "external": false,
      "loc": "arch/x86/kernel/static_call.c:28",
      "file": "arch/x86/kernel/static_call.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/static_call.c:__static_call_fixup",
        "arch/x86/kernel/static_call.c:arch_static_call_transform",
        "arch/x86/kernel/static_call.c:arch_static_call_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594677536,
      "name": "__static_call_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
void __static_call_transform(void * insn, enum insn_type type, void * func, bool modinit)
```

```json
{
  "name": "__static_call_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596412944,
      "name": "__static_call_transform",
      "external": false,
      "loc": "arch/x86/kernel/static_call.c:53",
      "file": "arch/x86/kernel/static_call.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/static_call.c:__static_call_fixup",
        "arch/x86/kernel/static_call.c:arch_static_call_transform",
        "arch/x86/kernel/static_call.c:arch_static_call_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596412944,
      "name": "__static_call_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
void __static_call_transform(void * insn, enum insn_type type, void * func, bool modinit)
```

```json
{
  "name": "__static_call_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596952784,
      "name": "__static_call_transform",
      "external": false,
      "loc": "arch/x86/kernel/static_call.c:53",
      "file": "arch/x86/kernel/static_call.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/static_call.c:__static_call_fixup",
        "arch/x86/kernel/static_call.c:arch_static_call_transform",
        "arch/x86/kernel/static_call.c:arch_static_call_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596952784,
      "name": "__static_call_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
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
void __static_call_transform(void * insn, enum insn_type type, void * func, bool modinit)
```

```json
{
  "name": "__static_call_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597880304,
      "name": "__static_call_transform",
      "external": false,
      "loc": "arch/x86/kernel/static_call.c:53",
      "file": "arch/x86/kernel/static_call.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/static_call.c:__static_call_fixup",
        "arch/x86/kernel/static_call.c:arch_static_call_transform",
        "arch/x86/kernel/static_call.c:arch_static_call_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597880304,
      "name": "__static_call_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
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
void __static_call_transform(void * insn, enum insn_type type, void * func)
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
<code>bool modinit</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
