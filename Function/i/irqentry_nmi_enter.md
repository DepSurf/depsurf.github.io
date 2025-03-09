# Function: <code>irqentry_nmi_enter</code>

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
irqentry_state_t irqentry_nmi_enter(struct pt_regs * regs)
```

```json
{
  "name": "irqentry_nmi_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591659632,
      "name": "irqentry_nmi_enter",
      "external": true,
      "loc": "kernel/entry/common.c:436",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_double_fault",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/cpu/mce/core.c:exc_machine_check",
        "arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591659632,
      "name": "irqentry_nmi_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
irqentry_state_t irqentry_nmi_enter(struct pt_regs * regs)
```

```json
{
  "name": "irqentry_nmi_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591603312,
      "name": "irqentry_nmi_enter",
      "external": true,
      "loc": "kernel/entry/common.c:445",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_double_fault",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/cpu/mce/core.c:exc_machine_check",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591603312,
      "name": "irqentry_nmi_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
irqentry_state_t irqentry_nmi_enter(struct pt_regs * regs)
```

```json
{
  "name": "irqentry_nmi_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592776208,
      "name": "irqentry_nmi_enter",
      "external": true,
      "loc": "kernel/entry/common.c:443",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_double_fault",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/cpu/mce/core.c:exc_machine_check",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592776208,
      "name": "irqentry_nmi_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
irqentry_state_t irqentry_nmi_enter(struct pt_regs * regs)
```

```json
{
  "name": "irqentry_nmi_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594673872,
      "name": "irqentry_nmi_enter",
      "external": true,
      "loc": "kernel/entry/common.c:443",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_double_fault",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/cpu/mce/core.c:exc_machine_check",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594673872,
      "name": "irqentry_nmi_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
irqentry_state_t irqentry_nmi_enter(struct pt_regs * regs)
```

```json
{
  "name": "irqentry_nmi_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596407920,
      "name": "irqentry_nmi_enter",
      "external": true,
      "loc": "kernel/entry/common.c:447",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_double_fault",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/cpu/mce/core.c:exc_machine_check",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596407920,
      "name": "irqentry_nmi_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
irqentry_state_t irqentry_nmi_enter(struct pt_regs * regs)
```

```json
{
  "name": "irqentry_nmi_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596939856,
      "name": "irqentry_nmi_enter",
      "external": true,
      "loc": "kernel/entry/common.c:448",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_double_fault",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/cpu/mce/core.c:exc_machine_check",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596939856,
      "name": "irqentry_nmi_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
irqentry_state_t irqentry_nmi_enter(struct pt_regs * regs)
```

```json
{
  "name": "irqentry_nmi_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597865344,
      "name": "irqentry_nmi_enter",
      "external": true,
      "loc": "kernel/entry/common.c:363",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/traps.c:exc_double_fault",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/cpu/mce/core.c:exc_machine_check",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597865344,
      "name": "irqentry_nmi_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
irqentry_state_t irqentry_nmi_enter(struct pt_regs * regs)
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
