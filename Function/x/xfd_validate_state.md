# Function: <code>xfd_validate_state</code>

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
void xfd_validate_state(struct fpstate * fpstate, u64 mask, bool rstor)
```

```json
{
  "name": "xfd_validate_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579201472,
      "name": "xfd_validate_state",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1409",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear_user_states",
        "arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate",
        "arch/x86/kernel/fpu/core.c:os_xsave",
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user",
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:os_xsave"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579201472,
      "name": "xfd_validate_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void xfd_validate_state(struct fpstate * fpstate, u64 mask, bool rstor)
```

```json
{
  "name": "xfd_validate_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579256512,
      "name": "xfd_validate_state",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1455",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear_user_states",
        "arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate",
        "arch/x86/kernel/fpu/core.c:os_xsave",
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user",
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:os_xsave"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256512,
      "name": "xfd_validate_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void xfd_validate_state(struct fpstate * fpstate, u64 mask, bool rstor)
```

```json
{
  "name": "xfd_validate_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579262928,
      "name": "xfd_validate_state",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1460",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear_user_states",
        "arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate",
        "arch/x86/kernel/fpu/core.c:os_xsave",
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user",
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:os_xsave"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262928,
      "name": "xfd_validate_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void xfd_validate_state(struct fpstate * fpstate, u64 mask, bool rstor)
```

```json
{
  "name": "xfd_validate_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579292752,
      "name": "xfd_validate_state",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1459",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear_user_states",
        "arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate",
        "arch/x86/kernel/fpu/core.c:os_xsave",
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user",
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:os_xsave"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579292752,
      "name": "xfd_validate_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void xfd_validate_state(struct fpstate * fpstate, u64 mask, bool rstor)
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
