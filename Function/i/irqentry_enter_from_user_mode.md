# Function: <code>irqentry_enter_from_user_mode</code>

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
void irqentry_enter_from_user_mode(struct pt_regs * regs)
```

```json
{
  "name": "irqentry_enter_from_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591659984,
      "name": "irqentry_enter_from_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:306",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:noist_exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check",
        "kernel/entry/common.c:irqentry_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591659984,
      "name": "irqentry_enter_from_user_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1
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
void irqentry_enter_from_user_mode(struct pt_regs * regs)
```

```json
{
  "name": "irqentry_enter_from_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591603664,
      "name": "irqentry_enter_from_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:307",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:noist_exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check",
        "arch/x86/kernel/sev.c:user_exc_vmm_communication",
        "kernel/entry/common.c:irqentry_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591603664,
      "name": "irqentry_enter_from_user_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1
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
void irqentry_enter_from_user_mode(struct pt_regs * regs)
```

```json
{
  "name": "irqentry_enter_from_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592776544,
      "name": "irqentry_enter_from_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:305",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:noist_exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check",
        "arch/x86/kernel/sev.c:user_exc_vmm_communication",
        "kernel/entry/common.c:irqentry_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592776544,
      "name": "irqentry_enter_from_user_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1
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
void irqentry_enter_from_user_mode(struct pt_regs * regs)
```

```json
{
  "name": "irqentry_enter_from_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594674224,
      "name": "irqentry_enter_from_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:299",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:noist_exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check",
        "arch/x86/kernel/sev.c:user_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594674224,
      "name": "irqentry_enter_from_user_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5
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
void irqentry_enter_from_user_mode(struct pt_regs * regs)
```

```json
{
  "name": "irqentry_enter_from_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596408416,
      "name": "irqentry_enter_from_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:301",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:noist_exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check",
        "arch/x86/kernel/sev.c:user_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596408416,
      "name": "irqentry_enter_from_user_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5
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
void irqentry_enter_from_user_mode(struct pt_regs * regs)
```

```json
{
  "name": "irqentry_enter_from_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596940448,
      "name": "irqentry_enter_from_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:302",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:noist_exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check",
        "arch/x86/kernel/sev.c:user_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596940448,
      "name": "irqentry_enter_from_user_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 5
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
void irqentry_enter_from_user_mode(struct pt_regs * regs)
```

```json
{
  "name": "irqentry_enter_from_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597866304,
      "name": "irqentry_enter_from_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:217",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:noist_exc_debug",
        "arch/x86/kernel/traps.c:exc_int3",
        "arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check",
        "arch/x86/kernel/sev.c:user_exc_vmm_communication",
        "kernel/entry/common.c:irqentry_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597866304,
      "name": "irqentry_enter_from_user_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void irqentry_enter_from_user_mode(struct pt_regs * regs)
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
