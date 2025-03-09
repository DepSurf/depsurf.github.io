# Function: <code>irq_modify_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579752848,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:829",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:hpet_msi_free",
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/tps65912-irq.c:tps65912_irq_init",
        "drivers/mfd/tps65912-irq.c:tps65912_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752848,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579775392,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:887",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/msi.c:hpet_msi_free",
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579775392,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802240,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:896",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/msi.c:hpet_msi_free",
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802240,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579799408,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1001",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/msi.c:hpet_msi_free",
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579799408,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579833296,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1024",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/msi.c:hpet_msi_free",
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579833296,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579867152,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1022",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/msi.c:hpet_msi_free",
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867152,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579914176,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1022",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/msi.c:hpet_msi_free",
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914176,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579951776,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1094",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/msi.c:hpet_msi_free",
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951776,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580001632,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1094",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/msi.c:hpet_msi_free",
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580001632,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050912,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1094",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/apic/msi.c:hpet_msi_free",
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_remove_irq",
        "kernel/irq/irqdomain.c:irq_domain_insert_irq",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050912,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580033568,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1083",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_msi_free",
        "arch/x86/kernel/hpet.c:hpet_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_remove_irq",
        "kernel/irq/irqdomain.c:irq_domain_insert_irq",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580033568,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580034464,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1086",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_msi_free",
        "arch/x86/kernel/hpet.c:hpet_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034464,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580166992,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1086",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_msi_free",
        "arch/x86/kernel/hpet.c:hpet_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580166992,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580313584,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1084",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_msi_free",
        "arch/x86/kernel/hpet.c:hpet_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irq_sim.c:irq_sim_domain_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580313584,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580527264,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1086",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/irqinit.c:init_ISA_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_msi_free",
        "arch/x86/kernel/hpet.c:hpet_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate_locked",
        "kernel/irq/irq_sim.c:irq_sim_domain_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580527264,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580600320,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1101",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/irqinit.c:init_ISA_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_msi_free",
        "arch/x86/kernel/hpet.c:hpet_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate_locked",
        "kernel/irq/irq_sim.c:irq_sim_domain_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580600320,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580664832,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1098",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/irqinit.c:init_ISA_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr",
        "arch/x86/kernel/hpet.c:hpet_msi_free",
        "arch/x86/kernel/hpet.c:hpet_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_free",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_domain_associate_locked",
        "kernel/irq/irq_sim.c:irq_sim_domain_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580664832,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491195336,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1094",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_teardown",
        "virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_init",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "drivers/irqchip/irq-sun4i.c:sun4i_irq_map",
        "drivers/irqchip/irq-gic.c:gic_irq_domain_map",
        "drivers/irqchip/irq-gic.c:gic_irq_domain_map",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v4.c:its_unmap_vlpi",
        "drivers/irqchip/irq-gic-v4.c:its_map_vlpi",
        "drivers/irqchip/irq-gic-v4.c:its_map_vlpi",
        "drivers/irqchip/irq-partition-percpu.c:partition_domain_alloc",
        "drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_irq_map",
        "drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_irq_map",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_ap_alloc",
        "drivers/irqchip/qcom-irq-combiner.c:combiner_irq_map",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_irq_map",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_legacy_map",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_detach_irq",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/stmpe.c:stmpe_irq_map",
        "drivers/mfd/stmpe.c:stmpe_irq_map",
        "drivers/mfd/tc3589x.c:tc3589x_irq_map",
        "drivers/mfd/tc3589x.c:tc3589x_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_map",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_map",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/edac/altera_edac.c:a10_eccmgr_irqdomain_map",
        "drivers/perf/arm_pmu.c:armpmu_request_irq",
        "drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491195336,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225215908,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1094",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "drivers/irqchip/exynos-combiner.c:combiner_irq_domain_map",
        "drivers/irqchip/irq-hip04.c:hip04_irq_domain_map",
        "drivers/irqchip/irq-hip04.c:hip04_irq_domain_map",
        "drivers/irqchip/irq-gic.c:gic_irq_domain_map",
        "drivers/irqchip/irq-gic.c:gic_irq_domain_map",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc",
        "drivers/irqchip/irq-gic-v4.c:its_unmap_vlpi",
        "drivers/irqchip/irq-gic-v4.c:its_map_vlpi",
        "drivers/irqchip/irq-gic-v4.c:its_map_vlpi",
        "drivers/irqchip/irq-partition-percpu.c:partition_domain_alloc",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_irq_map",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_irq_map",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_irq_map",
        "drivers/irqchip/irq-rda-intc.c:rda_irq_map",
        "drivers/irqchip/irq-rda-intc.c:rda_irq_map",
        "drivers/irqchip/irq-aspeed-vic.c:avic_map",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/gpio/gpio-htc-egpio.c:egpio_probe",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_detach_irq",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/asic3.c:asic3_irq_remove",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/stmpe.c:stmpe_irq_map",
        "drivers/mfd/stmpe.c:stmpe_irq_map",
        "drivers/mfd/tc3589x.c:tc3589x_irq_map",
        "drivers/mfd/tc3589x.c:tc3589x_irq_map",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/mfd/tc6393xb.c:tc6393xb_detach_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/tps65217.c:tps65217_irq_map",
        "drivers/mfd/tps65217.c:tps65217_irq_map",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_map",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_map",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/clocksource/timer-tegra.c:tegra_init_timer",
        "drivers/clocksource/exynos_mct.c:mct_init_dt",
        "drivers/memory/omap-gpmc.c:gpmc_irq_map",
        "drivers/perf/arm_pmu.c:armpmu_request_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225215908,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284098224,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1094",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/sysdev/i8259.c:i8259_host_map",
        "arch/powerpc/sysdev/i8259.c:i8259_host_map",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/stmpe.c:stmpe_irq_map",
        "drivers/mfd/stmpe.c:stmpe_irq_map",
        "drivers/mfd/tc3589x.c:tc3589x_irq_map",
        "drivers/mfd/tc3589x.c:tc3589x_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_map",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_map",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284098224,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271738860,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1094",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "drivers/irqchip/irq-sifive-plic.c:plic_irqdomain_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/stmpe.c:stmpe_irq_map",
        "drivers/mfd/stmpe.c:stmpe_irq_map",
        "drivers/mfd/tc3589x.c:tc3589x_irq_map",
        "drivers/mfd/tc3589x.c:tc3589x_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_map",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_map",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271738860,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579970368,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1094",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/msi.c:hpet_msi_free",
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970368,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908192,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1094",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/msi.c:hpet_msi_free",
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/irq_sim.c:irq_sim_init",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908192,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579961904,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1094",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/msi.c:hpet_msi_free",
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579961904,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void irq_modify_status(unsigned int irq, long unsigned int clr, long unsigned int set)
```

```json
{
  "name": "irq_modify_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008368,
      "name": "irq_modify_status",
      "external": true,
      "loc": "kernel/irq/chip.c:1094",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/io_apic.c:mp_register_handler",
        "arch/x86/kernel/apic/msi.c:hpet_msi_free",
        "arch/x86/kernel/apic/msi.c:hpet_msi_init",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "arch/x86/platform/uv/uv_irq.c:uv_domain_alloc",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_map_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008368,
      "name": "irq_modify_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
