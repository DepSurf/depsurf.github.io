# Function: <code>copy_uabi_from_kernel_to_xstate</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int copy_uabi_from_kernel_to_xstate(struct xregs_state * xsave, const void * kbuf)
```

```json
{
  "name": "copy_uabi_from_kernel_to_xstate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579157264,
      "name": "copy_uabi_from_kernel_to_xstate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1162",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579157264,
      "name": "copy_uabi_from_kernel_to_xstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int copy_uabi_from_kernel_to_xstate(struct fpstate * fpstate, const void * kbuf)
```

```json
{
  "name": "copy_uabi_from_kernel_to_xstate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579201248,
      "name": "copy_uabi_from_kernel_to_xstate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1267",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu_copy_uabi_to_guest_fpstate",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579201248,
      "name": "copy_uabi_from_kernel_to_xstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int copy_uabi_from_kernel_to_xstate(struct fpstate * fpstate, const void * kbuf, u32 * pkru)
```

```json
{
  "name": "copy_uabi_from_kernel_to_xstate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579256192,
      "name": "copy_uabi_from_kernel_to_xstate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1313",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu_copy_uabi_to_guest_fpstate",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256192,
      "name": "copy_uabi_from_kernel_to_xstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int copy_uabi_from_kernel_to_xstate(struct fpstate * fpstate, const void * kbuf, u32 * pkru)
```

```json
{
  "name": "copy_uabi_from_kernel_to_xstate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579262608,
      "name": "copy_uabi_from_kernel_to_xstate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1318",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu_copy_uabi_to_guest_fpstate",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262608,
      "name": "copy_uabi_from_kernel_to_xstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int copy_uabi_from_kernel_to_xstate(struct fpstate * fpstate, const void * kbuf, u32 * pkru)
```

```json
{
  "name": "copy_uabi_from_kernel_to_xstate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579292432,
      "name": "copy_uabi_from_kernel_to_xstate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1317",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu_copy_uabi_to_guest_fpstate",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579292432,
      "name": "copy_uabi_from_kernel_to_xstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int copy_uabi_from_kernel_to_xstate(struct xregs_state * xsave, const void * kbuf)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fpstate * fpstate</code>
</li>
<li>
<b>Param removed. </b>
<code>struct xregs_state * xsave</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 * pkru</code>
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
