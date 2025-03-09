# Function: <code>paravirt_write_msr_safe</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595118675,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:138",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579361431,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:138",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578912950,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:138",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595128396,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:138",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578921693,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:138",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595133686,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:138",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579028681,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:138",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl",
        "arch/x86/kernel/process_64.c:do_arch_prctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111213,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:138",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118511,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:138",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145955,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:138",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156701,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:138",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579172252,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:138",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583446413,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:138",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583449395,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:138",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584076542,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:138",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595361383,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579379255,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578913382,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595371204,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578921933,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595376356,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579028341,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl",
        "arch/x86/kernel/process_64.c:do_arch_prctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109757,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579117263,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595417610,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579145994,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155171,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165997,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579182524,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583574061,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583577043,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584219279,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596279420,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578896965,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578906790,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596289347,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578915165,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596293196,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596308140,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579020661,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579101437,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109307,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596337028,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579144329,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153059,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165853,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579181276,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264176,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583612765,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583615763,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584290137,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586813782,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:129",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602595738,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578898405,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578908918,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602606135,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578917085,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602611019,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602626140,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579024053,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579112864,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579122476,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602655199,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579159337,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579167891,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579180557,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579196744,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583858765,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583861465,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584688681,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587298038,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602764080,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578900242,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578911277,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602774738,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919597,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602779310,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602794976,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579028204,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119216,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579132190,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602826366,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170756,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179475,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191989,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579208646,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584059221,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584062057,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584914194,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587600803,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:125",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604558218,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578901469,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578912845,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604569570,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578921261,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604573138,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604589170,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579124845,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579139094,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160196,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168883,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181413,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604634154,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579232268,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584143349,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584146185,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585018098,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587728451,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604652413,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578893333,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578917389,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604664147,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578926285,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604668243,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604684546,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134523,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151040,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172284,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181363,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579193957,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604731385,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245411,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584333477,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584336249,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585221780,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588011796,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:187",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604664685,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578894373,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919373,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604676645,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578928253,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604680771,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604696978,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136443,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153320,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174725,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183651,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196261,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604744498,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247635,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584468149,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584470921,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585358212,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588219492,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int paravirt_write_msr_safe(unsigned int msr, unsigned int low, unsigned int high)
```

```json
{
  "name": "paravirt_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578884224,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578906597,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578924493,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578933690,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ]
    },
    {
      "addr": 18446744071578934253,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609031416,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609047921,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152331,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164104,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172326,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:amd_detect_ppin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192805,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204416,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216885,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071609089884,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:__check_quirks_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272340,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585031893,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585034999,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586066516,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589082308,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:181",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_turbo_max_3.c:get_oc_core_priority"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578910129,
      "name": "paravirt_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578930976,
      "name": "paravirt_write_msr_safe.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int paravirt_write_msr_safe(unsigned int msr, unsigned int low, unsigned int high)
```

```json
{
  "name": "paravirt_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591238780,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578903381,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923389,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612089086,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578934874,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ]
    },
    {
      "addr": 18446744071578935437,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612094813,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612111265,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149499,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161336,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168847,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:amd_detect_ppin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579188589,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579199680,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211612,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071612153531,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:__check_quirks_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279732,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585183781,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585187079,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586188468,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589083284,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:179",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_turbo_max_3.c:get_oc_core_priority"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591239956,
      "name": "paravirt_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578932160,
      "name": "paravirt_write_msr_safe.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int paravirt_write_msr_safe(unsigned int msr, unsigned int low, unsigned int high)
```

```json
{
  "name": "paravirt_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578873155,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578907494,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578928013,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614228597,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578937800,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ]
    },
    {
      "addr": 18446744071578940285,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614234984,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614251105,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155787,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168379,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579175385,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194946,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214028,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071614293946,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282500,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585065733,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585068967,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586063844,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588573427,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588969940,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_turbo_max_3.c:get_oc_core_priority"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591182897,
      "name": "paravirt_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578936880,
      "name": "paravirt_write_msr_safe.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int paravirt_write_msr_safe(unsigned int msr, unsigned int low, unsigned int high)
```

```json
{
  "name": "paravirt_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578875233,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578911024,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578933005,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615147219,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578944815,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ]
    },
    {
      "addr": 18446744071578947885,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615154486,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615171521,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579185371,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201387,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209067,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579230178,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251996,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071615219593,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:check_quirks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325892,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585512469,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585515703,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586557536,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248341,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:notify_hwp_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589688196,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:196",
      "file": "drivers/platform/x86/intel/turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592040079,
      "name": "paravirt_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071578943712,
      "name": "paravirt_write_msr_safe.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int paravirt_write_msr_safe(unsigned int msr, unsigned int low, unsigned int high)
```

```json
{
  "name": "paravirt_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578872479,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578916680,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:check_msr"
      ]
    },
    {
      "addr": 18446744071578941309,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616911878,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578953431,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ]
    },
    {
      "addr": 18446744071578956573,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616919830,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616937357,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233043,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:ppin_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251393,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579260532,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579281208,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579304300,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071616993422,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:check_quirks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385921,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586663125,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586667179,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587818062,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590714901,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:notify_hwp_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590997504,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/amd-pstate.c:pstate_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591031239,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591194132,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "drivers/platform/x86/intel/turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593806256,
      "name": "paravirt_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071578952208,
      "name": "paravirt_write_msr_safe.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
  "name": "paravirt_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578878629,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578931026,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578958301,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627509375,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627510514,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578973469,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627519166,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627543845,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292227,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:ppin_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579312833,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322741,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346312,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579372387,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:mtrr_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627619322,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579463377,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587911061,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587915659,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589159294,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592386453,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:notify_hwp_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592704816,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/amd-pstate.c:pstate_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592741799,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592932916,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "drivers/platform/x86/intel/turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority"
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
  "name": "paravirt_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578876565,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578929074,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578957485,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619254303,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619255426,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578972717,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619264350,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619290014,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298771,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:ppin_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319969,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331503,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_ibpb_brtype_microcode",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_spectral_chicken"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355192,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579381683,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:mtrr_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619374867,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579475908,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588185013,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588189691,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589452478,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592810983,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "drivers/thermal/intel/intel_tcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_tcc.c:intel_tcc_set_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592815317,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:notify_hwp_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593178919,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593382628,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "drivers/platform/x86/intel/turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578898869,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578952290,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980877,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621546769,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621548002,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:__p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578997485,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621557022,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621582510,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328222,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:ppin_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579349985,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360431,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385128,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411324,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071621668338,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:__check_quirks_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579506676,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588477013,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588481691,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589760462,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593559911,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "drivers/thermal/intel/intel_tcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_tcc.c:intel_tcc_set_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593564213,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:notify_hwp_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593932743,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594127348,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:206",
      "file": "drivers/platform/x86/intel/turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority"
      ],
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604590957,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578894373,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919373,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604602917,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578928253,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604607076,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604623266,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136827,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153688,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174981,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183907,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579195109,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604670801,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579246483,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584436901,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584439673,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585158980,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587831188,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604668781,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578894309,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919309,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604680741,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578928189,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604684867,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604701074,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136379,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153240,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174645,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183571,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196181,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604748564,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247539,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584419813,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584422585,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585309796,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588173972,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604668786,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578894869,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919853,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604680761,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578928765,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604684823,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604701090,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141499,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579158376,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179829,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579188819,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201461,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604748610,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253107,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584525861,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584528713,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585415940,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588291828,
      "name": "paravirt_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:175",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int paravirt_write_msr_safe(unsigned int msr, unsigned int low, unsigned int high)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int paravirt_write_msr_safe(unsigned int msr, unsigned int low, unsigned int high)
```
</details>
</li>
</ul>
