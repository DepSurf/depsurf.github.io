# Function: <code>__copy_xstate_to_uabi_buf</code>

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
void __copy_xstate_to_uabi_buf(struct membuf to, struct fpstate * fpstate, u32 pkru_val, enum xstate_copy_mode copy_mode)
```

```json
{
  "name": "__copy_xstate_to_uabi_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579198480,
      "name": "__copy_xstate_to_uabi_buf",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1063",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu_copy_guest_fpstate_to_uabi",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579198480,
      "name": "__copy_xstate_to_uabi_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2708
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
void __copy_xstate_to_uabi_buf(struct membuf to, struct fpstate * fpstate, u32 pkru_val, enum xstate_copy_mode copy_mode)
```

```json
{
  "name": "__copy_xstate_to_uabi_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579254960,
      "name": "__copy_xstate_to_uabi_buf",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1058",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu_copy_guest_fpstate_to_uabi",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579254960,
      "name": "__copy_xstate_to_uabi_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1137
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
void __copy_xstate_to_uabi_buf(struct membuf to, struct fpstate * fpstate, u32 pkru_val, enum xstate_copy_mode copy_mode)
```

```json
{
  "name": "__copy_xstate_to_uabi_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579261440,
      "name": "__copy_xstate_to_uabi_buf",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1065",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu_copy_guest_fpstate_to_uabi",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261440,
      "name": "__copy_xstate_to_uabi_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1079
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
void __copy_xstate_to_uabi_buf(struct membuf to, struct fpstate * fpstate, u64 xfeatures, u32 pkru_val, enum xstate_copy_mode copy_mode)
```

```json
{
  "name": "__copy_xstate_to_uabi_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291232,
      "name": "__copy_xstate_to_uabi_buf",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1062",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu_copy_guest_fpstate_to_uabi",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291232,
      "name": "__copy_xstate_to_uabi_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1089
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
void __copy_xstate_to_uabi_buf(struct membuf to, struct fpstate * fpstate, u32 pkru_val, enum xstate_copy_mode copy_mode)
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
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 xfeatures</code>
</li>
<li>
<b>Param reordered. </b>
<code>to, fpstate, pkru_val, copy_mode</code> ➡️ <code>to, fpstate, xfeatures, pkru_val, copy_mode</code>
</li>
</ul>
</details>
</li>
</ul>
