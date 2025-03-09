# Function: <code>cr4_update_irqsoff</code>

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
void cr4_update_irqsoff(long unsigned int set, long unsigned int clear)
```

```json
{
  "name": "cr4_update_irqsoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579147776,
      "name": "cr4_update_irqsoff",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:397",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:set_tsc_mode",
        "arch/x86/kernel/process.c:disable_TSC",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/reboot.c:vmxoff_nmi",
        "arch/x86/kernel/smp.c:__sysvec_reboot",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/mm/init.c:cr4_set_bits",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:cr4_update_pce",
        "arch/x86/mm/tlb.c:cr4_update_pce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579147776,
      "name": "cr4_update_irqsoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void cr4_update_irqsoff(long unsigned int set, long unsigned int clear)
```

```json
{
  "name": "cr4_update_irqsoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579144864,
      "name": "cr4_update_irqsoff",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:399",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:set_tsc_mode",
        "arch/x86/kernel/process.c:disable_TSC",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/reboot.c:emergency_vmx_disable_all",
        "arch/x86/kernel/reboot.c:vmxoff_nmi",
        "arch/x86/kernel/reboot.c:machine_real_restart",
        "arch/x86/kernel/smp.c:__sysvec_reboot",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/mm/init.c:cr4_set_bits",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:cr4_update_pce",
        "arch/x86/mm/tlb.c:cr4_update_pce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579144864,
      "name": "cr4_update_irqsoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void cr4_update_irqsoff(long unsigned int set, long unsigned int clear)
```

```json
{
  "name": "cr4_update_irqsoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579151216,
      "name": "cr4_update_irqsoff",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:398",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:set_tsc_mode",
        "arch/x86/kernel/process.c:disable_TSC",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:cr4_set_bits",
        "arch/x86/kernel/reboot.c:cr4_clear_bits",
        "arch/x86/kernel/smp.c:__sysvec_reboot",
        "arch/x86/mm/init.c:cr4_set_bits",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:cr4_update_pce",
        "arch/x86/mm/tlb.c:cr4_update_pce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579151216,
      "name": "cr4_update_irqsoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void cr4_update_irqsoff(long unsigned int set, long unsigned int clear)
```

```json
{
  "name": "cr4_update_irqsoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579179728,
      "name": "cr4_update_irqsoff",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:406",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:load_trampoline_pgtable",
        "arch/x86/kernel/process.c:set_tsc_mode",
        "arch/x86/kernel/process.c:disable_TSC",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:cr4_set_bits",
        "arch/x86/kernel/smp.c:__sysvec_reboot",
        "arch/x86/mm/init.c:cr4_set_bits",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:cr4_update_pce",
        "arch/x86/mm/tlb.c:cr4_update_pce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579179728,
      "name": "cr4_update_irqsoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void cr4_update_irqsoff(long unsigned int set, long unsigned int clear)
```

```json
{
  "name": "cr4_update_irqsoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579226384,
      "name": "cr4_update_irqsoff",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:462",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cr4_clear_bits",
        "arch/x86/kernel/cpu/common.c:cr4_set_bits",
        "arch/x86/mm/init.c:cr4_set_bits",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:cr4_update_pce",
        "arch/x86/mm/tlb.c:cr4_update_pce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579226384,
      "name": "cr4_update_irqsoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void cr4_update_irqsoff(long unsigned int set, long unsigned int clear)
```

```json
{
  "name": "cr4_update_irqsoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579284752,
      "name": "cr4_update_irqsoff",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:463",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cr4_clear_bits",
        "arch/x86/kernel/cpu/common.c:cr4_set_bits",
        "arch/x86/mm/init.c:cr4_set_bits",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:cr4_update_pce",
        "arch/x86/mm/tlb.c:cr4_update_pce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579284752,
      "name": "cr4_update_irqsoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void cr4_update_irqsoff(long unsigned int set, long unsigned int clear)
```

```json
{
  "name": "cr4_update_irqsoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291328,
      "name": "cr4_update_irqsoff",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:451",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cr4_clear_bits",
        "arch/x86/kernel/cpu/common.c:cr4_set_bits",
        "arch/x86/mm/init.c:cr4_set_bits",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:cr4_update_pce",
        "arch/x86/mm/tlb.c:cr4_update_pce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291328,
      "name": "cr4_update_irqsoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cr4_update_irqsoff(long unsigned int set, long unsigned int clear)
```

```json
{
  "name": "cr4_update_irqsoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579321895,
      "name": "cr4_update_irqsoff",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:432",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cr4_set_bits"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cr4_clear_bits",
        "arch/x86/mm/init.c:cr4_set_bits",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:cr4_update_pce",
        "arch/x86/mm/tlb.c:cr4_update_pce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322000,
      "name": "cr4_update_irqsoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void cr4_update_irqsoff(long unsigned int set, long unsigned int clear)
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
