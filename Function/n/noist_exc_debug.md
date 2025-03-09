# Function: <code>noist_exc_debug</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void noist_exc_debug(struct pt_regs * regs)
```

```json
{
  "name": "noist_exc_debug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591155744,
      "name": "noist_exc_debug",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:930",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xenpv_exc_debug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591155744,
      "name": "noist_exc_debug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void noist_exc_debug(struct pt_regs * regs)
```

```json
{
  "name": "noist_exc_debug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591648928,
      "name": "noist_exc_debug",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:1001",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xenpv_exc_debug",
        "arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591648928,
      "name": "noist_exc_debug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void noist_exc_debug(struct pt_regs * regs)
```

```json
{
  "name": "noist_exc_debug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591592736,
      "name": "noist_exc_debug",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:1003",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xenpv_exc_debug",
        "arch/x86/kernel/sev.c:user_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591592736,
      "name": "noist_exc_debug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void noist_exc_debug(struct pt_regs * regs)
```

```json
{
  "name": "noist_exc_debug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592764560,
      "name": "noist_exc_debug",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:1038",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xenpv_exc_debug",
        "arch/x86/kernel/sev.c:user_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592764560,
      "name": "noist_exc_debug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void noist_exc_debug(struct pt_regs * regs)
```

```json
{
  "name": "noist_exc_debug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594657632,
      "name": "noist_exc_debug",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:1169",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xenpv_exc_debug",
        "arch/x86/kernel/sev.c:user_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594657632,
      "name": "noist_exc_debug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void noist_exc_debug(struct pt_regs * regs)
```

```json
{
  "name": "noist_exc_debug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596391136,
      "name": "noist_exc_debug",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:1178",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xenpv_exc_debug",
        "arch/x86/kernel/sev.c:user_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596391136,
      "name": "noist_exc_debug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void noist_exc_debug(struct pt_regs * regs)
```

```json
{
  "name": "noist_exc_debug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596921360,
      "name": "noist_exc_debug",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:1179",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xenpv_exc_debug",
        "arch/x86/kernel/sev.c:user_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596921360,
      "name": "noist_exc_debug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void noist_exc_debug(struct pt_regs * regs)
```

```json
{
  "name": "noist_exc_debug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597847088,
      "name": "noist_exc_debug",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:1093",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xenpv_exc_debug",
        "arch/x86/kernel/sev.c:user_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597847088,
      "name": "noist_exc_debug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void noist_exc_debug(struct pt_regs * regs)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
