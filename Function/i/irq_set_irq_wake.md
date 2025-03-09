# Function: <code>irq_set_irq_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579741984,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:589",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/acpi/sleep.c:acpi_freeze_restore",
        "drivers/acpi/sleep.c:acpi_freeze_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741984,
      "name": "irq_set_irq_wake",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579764144,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:603",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/acpi/sleep.c:acpi_freeze_restore",
        "drivers/acpi/sleep.c:acpi_freeze_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579764144,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579791104,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:603",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/acpi/sleep.c:acpi_freeze_restore",
        "drivers/acpi/sleep.c:acpi_freeze_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791104,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579788800,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:580",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/acpi/sleep.c:acpi_freeze_restore",
        "drivers/acpi/sleep.c:acpi_freeze_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788800,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579822256,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:608",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/acpi/sleep.c:acpi_s2idle_restore",
        "drivers/acpi/sleep.c:acpi_s2idle_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822256,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579856048,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:641",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/acpi/sleep.c:acpi_s2idle_restore",
        "drivers/acpi/sleep.c:acpi_s2idle_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856048,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579903008,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:644",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/acpi/sleep.c:acpi_s2idle_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579903008,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579937792,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:702",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/acpi/sleep.c:acpi_s2idle_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937792,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579987920,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:695",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/acpi/sleep.c:acpi_s2idle_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987920,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580037136,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:778",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/acpi/sleep.c:acpi_s2idle_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037136,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580020000,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:848",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/acpi/sleep.c:acpi_s2idle_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020000,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580020640,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:848",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/acpi/sleep.c:acpi_s2idle_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020640,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580152880,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:872",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/acpi/sleep.c:acpi_s2idle_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152880,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580298944,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:887",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/acpi/sleep.c:acpi_s2idle_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580298944,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580510912,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:879",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/acpi/sleep.c:acpi_s2idle_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580510912,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580583040,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:885",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/acpi/sleep.c:acpi_s2idle_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580583040,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580647168,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:887",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_wake",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_wake",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/acpi/sleep.c:acpi_s2idle_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647168,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491175712,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:695",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake",
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_wake",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpio-mxc.c:gpio_set_wake_irq",
        "drivers/gpio/gpio-mxc.c:gpio_set_wake_irq",
        "drivers/gpio/gpio-pl061.c:pl061_irq_set_wake",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_resume",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_suspend",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/stmpe.c:stmpe_resume",
        "drivers/mfd/stmpe.c:stmpe_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77686.c:max77686_resume",
        "drivers/mfd/max77686.c:max77686_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/as3722.c:as3722_i2c_resume",
        "drivers/mfd/as3722.c:as3722_i2c_suspend",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_resume",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_suspend",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_resume",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_suspend",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491175712,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225201168,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:695",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_set_wake",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_wake",
        "drivers/gpio/gpio-htc-egpio.c:egpio_resume",
        "drivers/gpio/gpio-htc-egpio.c:egpio_suspend",
        "drivers/gpio/gpio-mxc.c:gpio_set_wake_irq",
        "drivers/gpio/gpio-mxc.c:gpio_set_wake_irq",
        "drivers/gpio/gpio-omap.c:omap_gpio_wake_enable",
        "drivers/gpio/gpio-pl061.c:pl061_irq_set_wake",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_irq_set_wake",
        "drivers/gpio/gpio-vf610.c:vf610_gpio_irq_set_wake",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_resume",
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_suspend",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/stmpe.c:stmpe_resume",
        "drivers/mfd/stmpe.c:stmpe_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/tps65217.c:tps65217_probe",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77686.c:max77686_resume",
        "drivers/mfd/max77686.c:max77686_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/as3722.c:as3722_i2c_resume",
        "drivers/mfd/as3722.c:as3722_i2c_suspend",
        "drivers/usb/musb/musb_core.c:musb_init_controller",
        "drivers/usb/musb/musb_core.c:musb_free",
        "drivers/rtc/rtc-omap.c:omap_rtc_resume",
        "drivers/rtc/rtc-omap.c:omap_rtc_suspend",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_resume",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_suspend",
        "drivers/rtc/rtc-twl.c:twl_rtc_alarm_irq_enable",
        "drivers/rtc/rtc-twl.c:twl_rtc_alarm_irq_enable",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake",
        "drivers/mmc/host/sdhci.c:sdhci_resume_host",
        "drivers/mmc/host/sdhci.c:sdhci_suspend_host",
        "sound/soc/soc-jack.c:snd_soc_jack_add_gpios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225201168,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284077808,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:695",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/stmpe.c:stmpe_resume",
        "drivers/mfd/stmpe.c:stmpe_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77686.c:max77686_resume",
        "drivers/mfd/max77686.c:max77686_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/as3722.c:as3722_i2c_resume",
        "drivers/mfd/as3722.c:as3722_i2c_suspend",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284077808,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271727194,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:695",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/stmpe.c:stmpe_resume",
        "drivers/mfd/stmpe.c:stmpe_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271727194,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579956656,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:695",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956656,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894512,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:695",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/acpi/sleep.c:acpi_s2idle_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894512,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579948192,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:695",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/acpi/sleep.c:acpi_s2idle_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948192,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
int irq_set_irq_wake(unsigned int irq, unsigned int on)
```

```json
{
  "name": "irq_set_irq_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579994624,
      "name": "irq_set_irq_wake",
      "external": true,
      "loc": "kernel/irq/manage.c:695",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/acpi/sleep.c:acpi_s2idle_prepare",
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_set_wake",
        "drivers/mfd/arizona-irq.c:arizona_set_irq_wake",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend",
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend",
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend",
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend",
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/tps6586x.c:tps6586x_irq_set_wake",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_set_wake",
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_set_cd_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994624,
      "name": "irq_set_irq_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
