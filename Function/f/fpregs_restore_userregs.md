# Function: <code>fpregs_restore_userregs</code>

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
  "name": "fpregs_restore_userregs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579145877,
      "name": "fpregs_restore_userregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:456",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:switch_fpu_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151488,
      "name": "fpregs_restore_userregs",
      "external": false,
      "loc": "arch/x86/include/asm/fpu/internal.h:456",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void fpregs_restore_userregs()
```

```json
{
  "name": "fpregs_restore_userregs",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579185365,
      "name": "fpregs_restore_userregs",
      "external": false,
      "loc": "arch/x86/kernel/fpu/context.h:55",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:switch_fpu_return"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu_clone"
      ]
    },
    {
      "addr": 18446744071579191328,
      "name": "fpregs_restore_userregs",
      "external": false,
      "loc": "arch/x86/kernel/fpu/context.h:55",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ]
    },
    {
      "addr": 18446744071579194736,
      "name": "fpregs_restore_userregs",
      "external": false,
      "loc": "arch/x86/kernel/fpu/context.h:55",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpstate_realloc",
        "arch/x86/kernel/fpu/xstate.c:fpstate_realloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579185120,
      "name": "fpregs_restore_userregs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071579191328,
      "name": "fpregs_restore_userregs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071579194736,
      "name": "fpregs_restore_userregs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fpregs_restore_userregs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579240885,
      "name": "fpregs_restore_userregs",
      "external": false,
      "loc": "arch/x86/kernel/fpu/context.h:55",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:switch_fpu_return",
        "arch/x86/kernel/fpu/core.c:fpu_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249818,
      "name": "fpregs_restore_userregs",
      "external": false,
      "loc": "arch/x86/kernel/fpu/context.h:55",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252911,
      "name": "fpregs_restore_userregs",
      "external": false,
      "loc": "arch/x86/kernel/fpu/context.h:55",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpstate_realloc"
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
  "name": "fpregs_restore_userregs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579247541,
      "name": "fpregs_restore_userregs",
      "external": false,
      "loc": "arch/x86/kernel/fpu/context.h:54",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:switch_fpu_return",
        "arch/x86/kernel/fpu/core.c:fpu_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256466,
      "name": "fpregs_restore_userregs",
      "external": false,
      "loc": "arch/x86/kernel/fpu/context.h:54",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579259419,
      "name": "fpregs_restore_userregs",
      "external": false,
      "loc": "arch/x86/kernel/fpu/context.h:54",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "fpregs_restore_userregs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579279046,
      "name": "fpregs_restore_userregs",
      "external": false,
      "loc": "arch/x86/kernel/fpu/context.h:54",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_lock_and_load",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return",
        "arch/x86/kernel/fpu/core.c:fpu_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286354,
      "name": "fpregs_restore_userregs",
      "external": false,
      "loc": "arch/x86/kernel/fpu/context.h:54",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289729,
      "name": "fpregs_restore_userregs",
      "external": false,
      "loc": "arch/x86/kernel/fpu/context.h:54",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
void fpregs_restore_userregs()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void fpregs_restore_userregs()
```
</details>
</li>
</ul>
