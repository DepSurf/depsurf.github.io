# Function: <code>register_syscore_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584399824,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:22",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/common.c:init_cpu_syscore",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/acpi/processor_idle.c:acpi_processor_syscore_init",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/firmware_class.c:firmware_class_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584399824,
      "name": "register_syscore_ops",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584735168,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:22",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/common.c:init_cpu_syscore",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_syscore_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/firmware_class.c:firmware_class_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584735168,
      "name": "register_syscore_ops",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584925040,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:22",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/common.c:init_cpu_syscore",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_syscore_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/iommu/amd_iommu_init.c:iommu_go_to_state",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/firmware_class.c:firmware_class_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584925040,
      "name": "register_syscore_ops",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585009952,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:22",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/common.c:init_cpu_syscore",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/iommu/amd_iommu_init.c:iommu_go_to_state",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/firmware_class.c:firmware_class_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585009952,
      "name": "register_syscore_ops",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585432128,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:22",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/common.c:init_cpu_syscore",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/iommu/amd_iommu_init.c:iommu_go_to_state",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/firmware_class.c:firmware_class_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585432128,
      "name": "register_syscore_ops",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585675280,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/common.c:init_cpu_syscore",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/amd_iommu_init.c:iommu_go_to_state",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585675280,
      "name": "register_syscore_ops",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585805536,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/common.c:init_cpu_syscore",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/amd_iommu_init.c:iommu_go_to_state",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805536,
      "name": "register_syscore_ops",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586038768,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/cpufreq/cpufreq.c:cpufreq_core_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586038768,
      "name": "register_syscore_ops",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586186368,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586186368,
      "name": "register_syscore_ops",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586948032,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586948032,
      "name": "register_syscore_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587033296,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033296,
      "name": "register_syscore_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586917088,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586917088,
      "name": "register_syscore_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587479424,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587479424,
      "name": "register_syscore_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588800272,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/aperfmperf.c:freq_invariance_enable",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588800272,
      "name": "register_syscore_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590296768,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/aperfmperf.c:freq_invariance_enable",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590296768,
      "name": "register_syscore_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590616832,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590616832,
      "name": "register_syscore_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590975936,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590975936,
      "name": "register_syscore_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498984752,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_init",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "kernel/time/sched_clock.c:sched_clock_syscore_init",
        "kernel/cpu_pm.c:cpu_pm_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init",
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init",
        "drivers/gpio/gpio-mxc.c:gpio_mxc_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_init",
        "drivers/soc/bcm/brcmstb/biuctrl.c:brcmstb_biuctrl_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/power/reset/sc27xx-poweroff.c:sc27xx_poweroff_probe",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498984752,
      "name": "register_syscore_ops",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231553344,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-exynos/suspend.c:exynos_pm_init",
        "arch/arm/mach-exynos/mcpm-exynos.c:exynos_mcpm_init",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "kernel/time/sched_clock.c:sched_clock_syscore_init",
        "kernel/cpu_pm.c:cpu_pm_init",
        "drivers/irqchip/exynos-combiner.c:combiner_of_init",
        "drivers/irqchip/irq-tegra.c:tegra_ictlr_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init",
        "drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init",
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init",
        "drivers/gpio/gpio-mxc.c:gpio_mxc_init",
        "drivers/clk/imx/clk-vf610.c:vf610_clocks_init",
        "drivers/clk/mvebu/common.c:mvebu_clk_gating_setup",
        "drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_init",
        "drivers/clk/samsung/clk.c:samsung_clk_extended_sleep_init",
        "drivers/clk/samsung/clk-exynos-clkout.c:exynos_clkout_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init",
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231553344,
      "name": "register_syscore_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292136880,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/sysdev/mpic.c:mpic_init_sys",
        "arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_init",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292136880,
      "name": "register_syscore_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276361916,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "kernel/time/sched_clock.c:sched_clock_syscore_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276361916,
      "name": "register_syscore_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585946736,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/xen/suspend.c:xen_setup_syscore_ops",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/base/firmware_loader/main.c:firmware_class_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585946736,
      "name": "register_syscore_ops",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585795824,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/hv/vmbus_drv.c:hv_acpi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585795824,
      "name": "register_syscore_ops",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586136384,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586136384,
      "name": "register_syscore_ops",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void register_syscore_ops(struct syscore_ops * ops)
```

```json
{
  "name": "register_syscore_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586244976,
      "name": "register_syscore_ops",
      "external": true,
      "loc": "drivers/base/syscore.c:21",
      "file": "drivers/base/syscore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/i8259.c:i8259A_init_ops",
        "arch/x86/kernel/i8237.c:i8237A_init_ops",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_init_finialize",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/kernel/apic/apic.c:init_lapic_sysfs",
        "arch/x86/kernel/apic/io_apic.c:ioapic_init_ops",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "kernel/irq/generic-chip.c:irq_gc_init_ops",
        "kernel/irq/pm.c:irq_pm_init_ops",
        "kernel/time/timekeeping.c:timekeeping_init_ops",
        "drivers/acpi/sleep.c:acpi_sleep_init",
        "drivers/acpi/pci_link.c:acpi_pci_link_init",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586244976,
      "name": "register_syscore_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
