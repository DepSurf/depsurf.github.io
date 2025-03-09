# Function: <code>__static_cpu_has_safe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool __static_cpu_has_safe(u16 bit)
```

```json
{
  "name": "__static_cpu_has_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579107872,
      "name": "__static_cpu_has_safe",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:1492",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/fpu/core.c:irq_fpu_usable",
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/core.c:fpu__restore",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_begin",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_begin",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_end",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_end",
        "arch/x86/kernel/fpu/core.c:__kernel_fpu_end",
        "arch/x86/kernel/fpu/core.c:fpu__save",
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:fpu__drop",
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe",
        "arch/x86/kernel/fpu/signal.c:fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe",
        "arch/x86/kernel/fpu/xstate.c:fpstate_sanitize_xstate",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579107872,
      "name": "__static_cpu_has_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
bool __static_cpu_has_safe(u16 bit)
```
</details>
</li>
</ul>
