# Function: <code>disable_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579741904,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:480",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/hpet.c:hpet_resume",
        "arch/x86/kernel/hpet.c:hpet_work",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741904,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579764064,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:494",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/hpet.c:hpet_work",
        "arch/x86/kernel/hpet.c:hpet_resume",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579764064,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579791024,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:494",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/hpet.c:hpet_work",
        "arch/x86/kernel/hpet.c:hpet_msi_resume",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791024,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579788720,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:465",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/hpet.c:hpet_work",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788720,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579822176,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:493",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/hpet.c:hpet_work",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822176,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855952,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:526",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/hpet.c:hpet_work",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855952,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579902912,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:529",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/hpet.c:hpet_work",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_suspend",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902912,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579937744,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:558",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/twl-core.c:twl_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_suspend",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937744,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579987872,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:551",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/twl-core.c:twl_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_suspend",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987872,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580046688,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:627",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/twl-core.c:twl_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_suspend",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046688,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580029888,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:697",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/twl-core.c:twl_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_suspend",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029888,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580030624,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:697",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/twl-core.c:twl_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_suspend",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/i2c/i2c-core-base.c:i2c_device_shutdown",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030624,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580163136,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:721",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/twl-core.c:twl_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/i2c/i2c-core-base.c:i2c_device_shutdown",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163136,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580309328,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:736",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/twl-core.c:twl_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/i2c/i2c-core-base.c:i2c_device_shutdown",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580309328,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580522128,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:728",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/twl-core.c:twl_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_suspend",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_suspend",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_shutdown",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/i2c/i2c-core-base.c:i2c_device_shutdown",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580522128,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580595056,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:733",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/twl-core.c:twl_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_suspend",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_suspend",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_shutdown",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/i2c/i2c-core-base.c:i2c_device_shutdown",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580595056,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580660480,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:735",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/twl-core.c:twl_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_suspend",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_suspend",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_shutdown",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/i2c/i2c-core-base.c:i2c_device_shutdown",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580660480,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491177832,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:551",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/vgic/vgic-v4.c:kvm_vgic_v4_disable_doorbell",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_pan_display",
        "drivers/video/fbdev/mx3fb.c:mx3fb_pan_display",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/tty/serial/imx.c:imx_uart_suspend",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/twl-core.c:twl_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77620.c:max77620_i2c_suspend",
        "drivers/mfd/max77686.c:max77686_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_suspend",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/as3722.c:as3722_i2c_suspend",
        "drivers/net/ethernet/freescale/fec_main.c:fec_poll_controller",
        "drivers/net/ethernet/smsc/smc91x.c:smc_poll_controller",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491177832,
      "name": "disable_irq",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225201120,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:551",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/fiq.c:disable_fiq",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/video/fbdev/mx3fb.c:mx3fb_pan_display",
        "drivers/video/fbdev/mx3fb.c:mx3fb_pan_display",
        "drivers/tty/serial/imx.c:imx_uart_suspend",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/twl-core.c:twl_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77620.c:max77620_i2c_suspend",
        "drivers/mfd/max77686.c:max77686_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_suspend",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/as3722.c:as3722_i2c_suspend",
        "drivers/net/ethernet/freescale/fec_main.c:fec_poll_controller",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/power/avs/smartreflex.c:sr_late_init",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios",
        "drivers/clocksource/dw_apb_timer.c:dw_apb_clockevent_pause"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225201120,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284077696,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:551",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_post_init",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/twl-core.c:twl_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77620.c:max77620_i2c_suspend",
        "drivers/mfd/max77686.c:max77686_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_suspend",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/as3722.c:as3722_i2c_suspend",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284077696,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271727130,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:551",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271727130,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579956608,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:551",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/nvme/host/pci.c:nvme_poll_irqdisable",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956608,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894464,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:551",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/nvme/host/pci.c:nvme_poll_irqdisable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894464,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579948144,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:551",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/twl-core.c:twl_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_suspend",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948144,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void disable_irq(unsigned int irq)
```

```json
{
  "name": "disable_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579994576,
      "name": "disable_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:551",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_resume_noirq",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/arizona-core.c:arizona_suspend",
        "drivers/mfd/twl-core.c:twl_suspend",
        "drivers/mfd/da9052-irq.c:da9052_disable_irq",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_suspend",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_shutdown",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_suspend",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_shutdown",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:write_update_fw",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994576,
      "name": "disable_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
