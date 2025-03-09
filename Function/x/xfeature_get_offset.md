# Function: <code>xfeature_get_offset</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int xfeature_get_offset(u64 xcomp_bv, int xfeature)
```

```json
{
  "name": "xfeature_get_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579195104,
      "name": "xfeature_get_offset",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:137",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:__xstate_request_perm",
        "arch/x86/kernel/fpu/xstate.c:__raw_xsave_addr",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579195104,
      "name": "xfeature_get_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
unsigned int xfeature_get_offset(u64 xcomp_bv, int xfeature)
```

```json
{
  "name": "xfeature_get_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579251328,
      "name": "xfeature_get_offset",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:137",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:__xstate_request_perm",
        "arch/x86/kernel/fpu/xstate.c:__raw_xsave_addr",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:init_xstate_size",
        "arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579251328,
      "name": "xfeature_get_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
unsigned int xfeature_get_offset(u64 xcomp_bv, int xfeature)
```

```json
{
  "name": "xfeature_get_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579257808,
      "name": "xfeature_get_offset",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:137",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:__xstate_request_perm",
        "arch/x86/kernel/fpu/xstate.c:__raw_xsave_addr",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:init_xstate_size",
        "arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579257808,
      "name": "xfeature_get_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
unsigned int xfeature_get_offset(u64 xcomp_bv, int xfeature)
```

```json
{
  "name": "xfeature_get_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579287648,
      "name": "xfeature_get_offset",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:138",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:__raw_xsave_addr",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:xstate_calculate_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287648,
      "name": "xfeature_get_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
unsigned int xfeature_get_offset(u64 xcomp_bv, int xfeature)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
