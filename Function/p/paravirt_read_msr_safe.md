# Function: <code>paravirt_read_msr_safe</code>

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
  "name": "paravirt_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595118452,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595121347,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361321,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:check_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595168020,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579107234,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:__print_cpu_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118793,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579125658,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579135698,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/kernel/cpu/mcheck/mce-severity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce-severity.c:mce_severity_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141402,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595183228,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172049,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363715,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595206505,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595210232,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579207902,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212821,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579214413,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583446317,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583449319,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584078364,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584689605,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586297780,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595518434,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586579006,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:133",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
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
  "name": "paravirt_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595361160,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595364096,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579379145,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:check_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579117517,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579132746,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579142738,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/cpu/mcheck/mce-severity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce-severity.c:mce_severity_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145951,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150080,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595426440,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579182321,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579381786,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595449392,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595453249,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219566,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579224533,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579226013,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583573965,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583576967,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584220949,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584876165,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586502228,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595774502,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586763326,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
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
  "name": "paravirt_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596279174,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596282811,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578896869,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:check_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106854,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109544,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579131882,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579141115,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/cpu/mcheck/mce-severity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce-severity.c:mce_severity_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579144286,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145386,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596346610,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181073,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201289,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596370471,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596374092,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217348,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222245,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579223059,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583612669,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583615687,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584291178,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584964831,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586626152,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586813975,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596705541,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586886574,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:124",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602595492,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602599160,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578898309,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:check_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120027,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579122239,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579146250,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579156018,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/cpu/mcheck/mce-severity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce-severity.c:mce_severity_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579159156,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160298,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602664705,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196541,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216758,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602688840,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602692599,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579235037,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579238309,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579239811,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583858669,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583861366,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584415913,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "drivers/acpi/acpi_lpit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584688970,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585386127,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587109080,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587298231,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071603036247,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587375261,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602763831,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602767513,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578900175,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:check_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127739,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579131949,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156554,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579167509,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/cpu/mcheck/mce-severity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce-severity.c:mce_severity_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170638,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176081,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602835993,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208445,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579228614,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602860692,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602864057,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247597,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251061,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579252323,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579298131,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584060470,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584061990,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584639353,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "drivers/acpi/acpi_lpit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584915483,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585628942,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587407380,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587600834,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071603208971,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587678952,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:120",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604557969,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604561752,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578901402,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:check_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134413,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138586,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141661,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579146042,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579156965,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160078,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161585,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604629979,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579232061,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252310,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604657629,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604660994,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271405,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274613,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579276131,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579322739,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584144598,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584146118,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584738457,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "drivers/acpi/acpi_lpit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585019387,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585756142,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587587300,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587728482,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071605019423,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587810040,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604652167,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578879596,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/events/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578903654,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579145160,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150259,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153310,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579158268,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579168997,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172201,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173697,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604727171,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245373,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266257,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604755575,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604759024,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579285725,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288985,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579290547,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579338068,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:apic_is_x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584334678,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584336182,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584940505,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "drivers/acpi/acpi_lpit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585222883,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585929798,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585987917,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587863476,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588009788,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_resume",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588011827,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071605132646,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588115560,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:182",
      "file": "arch/x86/power/cpu.c",
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
  "name": "paravirt_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604664439,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578880364,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/events/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578905254,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579039760,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579147420,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153290,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155048,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160764,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579171429,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174649,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176113,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604740296,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247597,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267905,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604769083,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604772549,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288478,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579294873,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579296531,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579342244,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:apic_is_x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584469350,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584470854,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585076297,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/acpi/acpi_lpit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585359315,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586072934,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586134925,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588068260,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588217436,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_resume",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588219523,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071605172991,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588322026,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 paravirt_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "paravirt_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578883896,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists"
      ]
    },
    {
      "addr": 18446744071578884843,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/events/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578910114,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579049782,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579162292,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164064,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr",
        "arch/x86/kernel/cpu/intel.c:init_intel_misc_features",
        "arch/x86/kernel/cpu/intel.c:init_intel_misc_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172288,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:amd_detect_ppin",
        "arch/x86/kernel/cpu/amd.c:amd_detect_ppin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173700,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579180191,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579189097,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192752,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579198155,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609086490,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272139,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279883,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295793,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071609114945,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609119143,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579317940,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:__irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324677,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579326336,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371828,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585033030,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585034694,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585780826,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "drivers/acpi/acpi_lpit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586066283,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586820564,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "drivers/iommu/amd/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888586,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588939524,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589082335,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_turbo_max_3.c:get_oc_core_priority"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589087341,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_resume",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609456772,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591141914,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578883896,
      "name": "paravirt_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071578910114,
      "name": "paravirt_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 paravirt_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "paravirt_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591238464,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists"
      ]
    },
    {
      "addr": 18446744071578880363,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/events/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591239941,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591243605,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579159353,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161296,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr",
        "arch/x86/kernel/cpu/intel.c:init_intel_misc_features",
        "arch/x86/kernel/cpu/intel.c:init_intel_misc_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168809,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:amd_detect_ppin",
        "arch/x86/kernel/cpu/amd.c:amd_detect_ppin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579169812,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184807,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579188508,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579193819,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612150253,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279531,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287259,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591259545,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071612179711,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612183878,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326261,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579327936,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591264781,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585184918,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585186774,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585901898,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "drivers/acpi/acpi_lpit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586188235,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586938730,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588951476,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589083311,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_turbo_max_3.c:get_oc_core_priority"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589088094,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_resume",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612532750,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591225999,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:174",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591238464,
      "name": "paravirt_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071591239941,
      "name": "paravirt_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 paravirt_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "paravirt_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578873000,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578882820,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/events/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591182882,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591187249,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579166265,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168336,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579175335,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176660,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191190,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194862,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579199691,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614289949,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282299,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289851,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591202460,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071614320164,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614324189,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614338918,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328981,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579330624,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591206983,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585066870,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585067830,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585779355,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/acpi/acpi_lpit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586065354,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586822573,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588839876,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588969967,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_turbo_max_3.c:get_oc_core_priority"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588977214,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_resume",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614675418,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591175231,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591182882,
      "name": "paravirt_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 paravirt_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "paravirt_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578875080,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578886700,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/events/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592040064,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592050433,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579197481,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201344,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209018,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210490,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579226342,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579230094,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579235563,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615215614,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325659,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334907,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592073456,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071615248780,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615253056,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615266949,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383765,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579385776,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592080214,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585513606,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585514566,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586263556,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/acpi/acpi_lpit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586560168,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587382717,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589535460,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589687704,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/platform/x86/intel/pmc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_resume",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_pkgc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589688223,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/platform/x86/intel/turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615635967,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592028843,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592040064,
      "name": "paravirt_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 paravirt_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "paravirt_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578872321,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578884442,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/events/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593806218,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:check_msr"
      ]
    },
    {
      "addr": 18446744071593816976,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227772,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:ppin_init",
        "arch/x86/kernel/cpu/common.c:ppin_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593828864,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio"
      ]
    },
    {
      "addr": 18446744071579246640,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251351,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579260500,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579261366,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579281141,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286998,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616989306,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385671,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593840045,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617025553,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617030119,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617042893,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579449098,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579451578,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593847460,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586664477,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586665693,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587506323,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "drivers/acpi/acpi_lpit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587819926,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588692843,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590618588,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "drivers/i2c/busses/i2c-designware-amdpsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_dw_amdpsp_probe_lock_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591028223,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591193025,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "drivers/platform/x86/intel/pmc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_resume",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_pkgc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591194169,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "drivers/platform/x86/intel/turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617448768,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593796085,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:msr_build_context"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593806218,
      "name": "paravirt_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593828864,
      "name": "paravirt_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
  "name": "paravirt_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578878382,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578889786,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/events/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578930974,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:check_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627549920,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286459,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:ppin_init",
        "arch/x86/kernel/cpu/common.c:ppin_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627597456,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579306672,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579312791,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322709,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323622,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346245,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579352534,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627613494,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579463127,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627656860,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627662259,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627667496,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627675099,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579536682,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579539162,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627699258,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587912573,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587913981,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588780067,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "drivers/acpi/acpi_lpit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589162336,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590171665,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592280400,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "drivers/i2c/busses/i2c-designware-amdpsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_dw_amdpsp_probe_lock_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592741673,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592930229,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "drivers/platform/x86/intel/pmc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_resume",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_pkgc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592932953,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "drivers/platform/x86/intel/turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628213271,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595739652,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:197",
      "file": "arch/x86/power/cpu.c",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578876318,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578887722,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/events/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578929022,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:check_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619296400,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293035,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:ppin_init",
        "arch/x86/kernel/cpu/common.c:ppin_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619351536,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313824,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319927,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330717,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_spectral_chicken",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579332182,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355125,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361494,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619369046,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579475703,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619413804,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619419219,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619424462,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619436065,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579549530,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579551978,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619457002,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588186525,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588187949,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589069491,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "drivers/acpi/acpi_lpit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589455648,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590485889,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592811629,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "drivers/thermal/intel/intel_tcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_tcc.c:intel_tcc_get_temp",
        "drivers/thermal/intel/intel_tcc.c:intel_tcc_set_offset",
        "drivers/thermal/intel/intel_tcc.c:intel_tcc_get_offset",
        "drivers/thermal/intel/intel_tcc.c:intel_tcc_get_tjmax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593178793,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593380045,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "drivers/platform/x86/intel/pmc/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_resume_common",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_pkgc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593382665,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "drivers/platform/x86/intel/turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619982231,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596265620,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:199",
      "file": "arch/x86/power/cpu.c",
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
  "name": "paravirt_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578898622,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists",
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578910021,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/events/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578952238,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:check_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621589876,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322299,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:ppin_init",
        "arch/x86/kernel/cpu/common.c:ppin_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621645472,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio",
        "arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344800,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579349943,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360411,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362262,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385061,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391366,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621662934,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579506471,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621709404,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621713933,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621720494,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621728673,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579577530,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579579754,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621753306,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available",
        "arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588478525,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588479949,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589375283,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "drivers/acpi/acpi_lpit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589763648,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590831875,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593560557,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "drivers/thermal/intel/intel_tcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_tcc.c:intel_tcc_get_temp",
        "drivers/thermal/intel/intel_tcc.c:intel_tcc_set_offset",
        "drivers/thermal/intel/intel_tcc.c:intel_tcc_get_offset",
        "drivers/thermal/intel/intel_tcc.c:intel_tcc_get_tjmax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593932617,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594127385,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "drivers/platform/x86/intel/turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622294807,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597147876,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:201",
      "file": "arch/x86/power/cpu.c",
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604590711,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578880364,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/events/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578905254,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579040112,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579147788,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153658,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155416,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161132,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579171685,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174905,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176369,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604666599,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579246445,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266609,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604695362,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698845,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287182,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579290681,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579292339,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579338148,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:apic_is_x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584438102,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584439606,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585005785,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/acpi/acpi_lpit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585160019,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585834054,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585895293,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587690404,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587829132,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_resume",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587831219,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071605061635,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587925674,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604668535,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578880300,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/events/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578905190,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579039696,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579147340,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153210,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154968,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160684,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579171349,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174569,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176033,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604744362,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247501,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267809,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604772946,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604776412,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288382,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579291881,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579293539,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579338068,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:apic_is_x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584421014,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584422518,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585027881,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/acpi/acpi_lpit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585310899,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586022950,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586084941,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588024404,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588171916,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_resume",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588174003,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071605149194,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588259082,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604668540,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578880652,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/events/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578905654,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579043360,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579152476,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579158346,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160104,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165820,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579176533,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179753,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181217,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604744408,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253069,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579273409,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604773224,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604776690,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294270,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579300713,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579302371,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579346516,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:apic_is_x2apic_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584527094,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584528646,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585134041,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/acpi/acpi_lpit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585417043,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586130902,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586193229,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588139876,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588289772,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_resume",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588291859,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071605177185,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588394602,
      "name": "paravirt_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
u64 paravirt_read_msr_safe(unsigned int msr, int * err)
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
u64 paravirt_read_msr_safe(unsigned int msr, int * err)
```
</details>
</li>
</ul>
