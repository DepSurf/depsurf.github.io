# Function: <code>irqentry_nmi_exit</code>

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
void irqentry_nmi_exit(struct pt_regs * regs, irqentry_state_t irq_state)
```

```json
{
  "name": "irqentry_nmi_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591659712,
      "name": "irqentry_nmi_exit",
      "external": true,
      "loc": "kernel/entry/common.c:455",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/cpu/mce/core.c:exc_machine_check",
        "arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591659712,
      "name": "irqentry_nmi_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void irqentry_nmi_exit(struct pt_regs * regs, irqentry_state_t irq_state)
```

```json
{
  "name": "irqentry_nmi_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591603392,
      "name": "irqentry_nmi_exit",
      "external": true,
      "loc": "kernel/entry/common.c:464",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/cpu/mce/core.c:exc_machine_check",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591603392,
      "name": "irqentry_nmi_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void irqentry_nmi_exit(struct pt_regs * regs, irqentry_state_t irq_state)
```

```json
{
  "name": "irqentry_nmi_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592776288,
      "name": "irqentry_nmi_exit",
      "external": true,
      "loc": "kernel/entry/common.c:462",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/cpu/mce/core.c:exc_machine_check",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592776288,
      "name": "irqentry_nmi_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void irqentry_nmi_exit(struct pt_regs * regs, irqentry_state_t irq_state)
```

```json
{
  "name": "irqentry_nmi_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594673952,
      "name": "irqentry_nmi_exit",
      "external": true,
      "loc": "kernel/entry/common.c:462",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/cpu/mce/core.c:exc_machine_check",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594673952,
      "name": "irqentry_nmi_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void irqentry_nmi_exit(struct pt_regs * regs, irqentry_state_t irq_state)
```

```json
{
  "name": "irqentry_nmi_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596408016,
      "name": "irqentry_nmi_exit",
      "external": true,
      "loc": "kernel/entry/common.c:467",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/cpu/mce/core.c:exc_machine_check",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596408016,
      "name": "irqentry_nmi_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void irqentry_nmi_exit(struct pt_regs * regs, irqentry_state_t irq_state)
```

```json
{
  "name": "irqentry_nmi_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596939984,
      "name": "irqentry_nmi_exit",
      "external": true,
      "loc": "kernel/entry/common.c:468",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/cpu/mce/core.c:exc_machine_check",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596939984,
      "name": "irqentry_nmi_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void irqentry_nmi_exit(struct pt_regs * regs, irqentry_state_t irq_state)
```

```json
{
  "name": "irqentry_nmi_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597865472,
      "name": "irqentry_nmi_exit",
      "external": true,
      "loc": "kernel/entry/common.c:383",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/cpu/mce/core.c:exc_machine_check",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597865472,
      "name": "irqentry_nmi_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void irqentry_nmi_exit(struct pt_regs * regs, irqentry_state_t irq_state)
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
