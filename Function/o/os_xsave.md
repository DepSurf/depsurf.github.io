# Function: <code>os_xsave</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "os_xsave",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579144610,
      "name": "os_xsave",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:292",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151037,
      "name": "os_xsave",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:292",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu_restore_sig"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
void os_xsave(struct fpstate * fpstate)
```

```json
{
  "name": "os_xsave",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579183232,
      "name": "os_xsave",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.h:177",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate"
      ]
    },
    {
      "addr": 18446744071579190928,
      "name": "os_xsave",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.h:177",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:__fpu_restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183232,
      "name": "os_xsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071579190928,
      "name": "os_xsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate ❓</summary>

```c
void os_xsave(struct fpstate * fpstate)
```

```json
{
  "name": "os_xsave",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579238112,
      "name": "os_xsave",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.h:177",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate"
      ]
    },
    {
      "addr": 18446744071579247280,
      "name": "os_xsave",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.h:177",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:__fpu_restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579238112,
      "name": "os_xsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071579247280,
      "name": "os_xsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate ❓</summary>

```c
void os_xsave(struct fpstate * fpstate)
```

```json
{
  "name": "os_xsave",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579244112,
      "name": "os_xsave",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.h:177",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate"
      ]
    },
    {
      "addr": 18446744071579253840,
      "name": "os_xsave",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.h:177",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:__fpu_restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579244112,
      "name": "os_xsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071579253840,
      "name": "os_xsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate ❓</summary>

```c
void os_xsave(struct fpstate * fpstate)
```

```json
{
  "name": "os_xsave",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579273056,
      "name": "os_xsave",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.h:178",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate"
      ]
    },
    {
      "addr": 18446744071579283824,
      "name": "os_xsave",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.h:178",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:__fpu_restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579273056,
      "name": "os_xsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071579283824,
      "name": "os_xsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void os_xsave(struct fpstate * fpstate)
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
