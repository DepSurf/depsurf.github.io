# Function: <code>enable_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579747216,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:546",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/hpet.c:hpet_resume",
        "arch/x86/kernel/hpet.c:hpet_work",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume",
        "drivers/net/phy/phy.c:phy_stop_interrupts",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/net/phy/phy.c:phy_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579747216,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579769504,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:560",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/hpet.c:hpet_work",
        "arch/x86/kernel/hpet.c:hpet_resume",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_suspend_late",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/net/phy/phy.c:phy_stop_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579769504,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579796432,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:560",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/hpet.c:hpet_work",
        "arch/x86/kernel/hpet.c:hpet_msi_resume",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/net/phy/phy.c:phy_stop_interrupts",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579796432,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579793680,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:537",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/hpet.c:hpet_work",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/net/phy/phy.c:phy_stop_interrupts",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579793680,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579827344,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:565",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/hpet.c:hpet_work",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579827344,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579861200,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:598",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/hpet.c:hpet_work",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579861200,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908208,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:601",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/hpet.c:hpet_work",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_resume",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908208,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579943600,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:645",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:enable_nmi",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl-core.c:twl_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_resume",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943600,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993744,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:638",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:enable_nmi",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl-core.c:twl_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_resume",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993744,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580041088,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:714",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "kernel/irq/manage.c:enable_nmi",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl-core.c:twl_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_resume",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580041088,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580024288,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:784",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "kernel/irq/manage.c:enable_nmi",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl-core.c:twl_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_resume",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580024288,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580024976,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:784",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:enable_nmi",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl-core.c:twl_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_resume",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580024976,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580157376,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:808",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:enable_nmi",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/twl-core.c:twl_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_resume",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580157376,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580303216,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:823",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:enable_nmi",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_complete",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/twl-core.c:twl_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_resume",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_resume",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580303216,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580515552,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:815",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:enable_nmi",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/acpi/ec.c:acpi_ec_unmask_events",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_complete",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/twl-core.c:twl_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_resume",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_resume",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580515552,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580588448,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:821",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:enable_nmi",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/acpi/ec.c:acpi_ec_unmask_events",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_complete",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/mfd/twl-core.c:twl_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_resume",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_resume",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580588448,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580652800,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:823",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:enable_nmi",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/acpi/ec.c:acpi_ec_unmask_events",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_complete",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/mfd/twl-core.c:twl_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_resume",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_resume",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580652800,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491184008,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:638",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/vgic/vgic-v4.c:kvm_vgic_v4_enable_doorbell",
        "kernel/irq/manage.c:enable_nmi",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/video/fbdev/mx3fb.c:mx3fb_pan_display",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/imx.c:imx_uart_resume",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl-core.c:twl_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77620.c:max77620_i2c_resume",
        "drivers/mfd/max77686.c:max77686_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_resume",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/as3722.c:as3722_i2c_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_poll_controller",
        "drivers/net/ethernet/smsc/smc91x.c:smc_poll_controller",
        "drivers/thermal/armada_thermal.c:armada_overheat_isr_thread",
        "drivers/perf/arm_pmu.c:arm_perf_starting_cpu",
        "drivers/perf/qcom_l2_pmu.c:l2cache_pmu_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491184008,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225206984,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:638",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/fiq.c:enable_fiq",
        "kernel/irq/manage.c:enable_nmi",
        "drivers/video/fbdev/mx3fb.c:mx3fb_pan_display",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/imx.c:imx_uart_resume",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl-core.c:twl_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77620.c:max77620_i2c_resume",
        "drivers/mfd/max77686.c:max77686_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_resume",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/as3722.c:as3722_i2c_resume",
        "drivers/mtd/nand/raw/omap2.c:omap_write_buf_irq_pref",
        "drivers/mtd/nand/raw/omap2.c:omap_write_buf_irq_pref",
        "drivers/mtd/nand/raw/omap2.c:omap_read_buf_irq_pref",
        "drivers/mtd/nand/raw/omap2.c:omap_read_buf_irq_pref",
        "drivers/net/ethernet/freescale/fec_main.c:fec_poll_controller",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_work",
        "drivers/thermal/armada_thermal.c:armada_overheat_isr_thread",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios",
        "drivers/clocksource/dw_apb_timer.c:dw_apb_clockevent_resume",
        "drivers/clocksource/timer-tegra.c:tegra_timer_setup",
        "drivers/clocksource/exynos_mct.c:exynos4_mct_starting_cpu",
        "drivers/perf/arm_pmu.c:arm_perf_starting_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225206984,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284086128,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:638",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/eeh_driver.c:eeh_set_irq_state",
        "arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_next_error",
        "arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_probe",
        "kernel/irq/manage.c:enable_nmi",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_wait_for_stat",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl-core.c:twl_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77620.c:max77620_i2c_resume",
        "drivers/mfd/max77686.c:max77686_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_resume",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/as3722.c:as3722_i2c_resume",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284086128,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271731682,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:638",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:enable_nmi",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max8997.c:max8997_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271731682,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579962480,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:638",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:enable_nmi",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/nvme/host/pci.c:nvme_poll_irqdisable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962480,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900320,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:638",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:enable_nmi",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/nvme/host/pci.c:nvme_poll_irqdisable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900320,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579954016,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:638",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:enable_nmi",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl-core.c:twl_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_resume",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579954016,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void enable_irq(unsigned int irq)
```

```json
{
  "name": "enable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580000400,
      "name": "enable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:638",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/i8259.c:make_8259A_irq",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/irq/manage.c:enable_nmi",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq_check",
        "drivers/base/power/wakeirq.c:dev_pm_enable_wake_irq",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_resume",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend_noirq",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/twl-core.c:twl_resume",
        "drivers/mfd/da903x.c:da903x_irq_work",
        "drivers/mfd/da9052-irq.c:da9052_enable_irq",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_resume",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_resume",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_resume",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask_handler",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000400,
      "name": "enable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
