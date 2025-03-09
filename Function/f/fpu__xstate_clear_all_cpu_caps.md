# Function: <code>fpu__xstate_clear_all_cpu_caps</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void fpu__xstate_clear_all_cpu_caps()
```

```json
{
  "name": "fpu__xstate_clear_all_cpu_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579088160,
      "name": "fpu__xstate_clear_all_cpu_caps",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:42",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:x86_noxsave_setup",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088160,
      "name": "fpu__xstate_clear_all_cpu_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void fpu__xstate_clear_all_cpu_caps()
```

```json
{
  "name": "fpu__xstate_clear_all_cpu_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579086448,
      "name": "fpu__xstate_clear_all_cpu_caps",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:58",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579086448,
      "name": "fpu__xstate_clear_all_cpu_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void fpu__xstate_clear_all_cpu_caps()
```

```json
{
  "name": "fpu__xstate_clear_all_cpu_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579084560,
      "name": "fpu__xstate_clear_all_cpu_caps",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:59",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579084560,
      "name": "fpu__xstate_clear_all_cpu_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void fpu__xstate_clear_all_cpu_caps()
```

```json
{
  "name": "fpu__xstate_clear_all_cpu_caps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579076192,
      "name": "fpu__xstate_clear_all_cpu_caps",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:59",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579076192,
      "name": "fpu__xstate_clear_all_cpu_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fpu__xstate_clear_all_cpu_caps()
```

```json
{
  "name": "fpu__xstate_clear_all_cpu_caps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602651869,
      "name": "fpu__xstate_clear_all_cpu_caps",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:73",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579084960,
      "name": "fpu__xstate_clear_all_cpu_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fpu__xstate_clear_all_cpu_caps()
```

```json
{
  "name": "fpu__xstate_clear_all_cpu_caps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602821809,
      "name": "fpu__xstate_clear_all_cpu_caps",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:73",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579090336,
      "name": "fpu__xstate_clear_all_cpu_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fpu__xstate_clear_all_cpu_caps()
```

```json
{
  "name": "fpu__xstate_clear_all_cpu_caps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604616953,
      "name": "fpu__xstate_clear_all_cpu_caps",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:73",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579095648,
      "name": "fpu__xstate_clear_all_cpu_caps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void fpu__xstate_clear_all_cpu_caps()
```
</details>
</li>
</ul>
