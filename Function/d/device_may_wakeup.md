# Function: <code>device_may_wakeup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool device_may_wakeup(struct device * dev)
```

```json
{
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579873274,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583249750,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_target_state",
        "drivers/pci/pci.c:__pci_enable_wake",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_dev_keep_suspended"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583348238,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583397116,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544730,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583550194,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_suspend_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583554500,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device"
      ]
    },
    {
      "addr": 18446744071583808479,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584103061,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584449165,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584450437,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:pm_dev_dbg",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584588037,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584671850,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584673077,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584674298,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584678197,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584680485,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_suspend",
        "drivers/mfd/max8997.c:max8997_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584683525,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_suspend",
        "drivers/mfd/max8998.c:max8998_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584701338,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585057143,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/mdio_bus.c:mdio_bus_phy_may_suspend",
        "drivers/net/phy/mdio_bus.c:mdio_bus_phy_may_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585197080,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585223203,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585268423,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585386597,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585412445,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585414965,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585432441,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585552665,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585624973,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_suspend",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585661495,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/power/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/charger-manager.c:cm_suspend_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583554500,
      "name": "device_may_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool device_may_wakeup(struct device * dev)
```

```json
{
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579902714,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583559352,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_keep_suspended",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_target_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583660267,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583711509,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583865896,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583873759,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_suspend_late",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583875943,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ]
    },
    {
      "addr": 18446744071584134731,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584436405,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584785373,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584798086,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584807367,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584936293,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585019674,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585020901,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585022122,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585025973,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585028250,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585031245,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585049002,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585437911,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585589272,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585616355,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585664343,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585782901,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585808432,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585810933,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585828478,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585946510,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586021537,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586058359,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/power/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/charger-manager.c:cm_suspend_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583875943,
      "name": "device_may_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool device_may_wakeup(struct device * dev)
```

```json
{
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579912970,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583696292,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_keep_suspended",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_target_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583797867,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583850149,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584004972,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584012813,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_suspend_late",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584014997,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ]
    },
    {
      "addr": 18446744071584282731,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584619897,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584977037,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584990022,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584999109,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585119653,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585203658,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585204885,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585206106,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585209957,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585212234,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585215229,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585232826,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585639351,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585776888,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585803891,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585852039,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585971637,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585997104,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585999605,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586017182,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586134958,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586187255,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586219084,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586256103,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584014997,
      "name": "device_may_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579921402,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583736404,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_keep_suspended",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583840827,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583891221,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584055003,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584063213,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_suspend_late",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584068426,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584360734,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584702921,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585061805,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585074882,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585083974,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:pm_genpd_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585201029,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585285741,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585286981,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585288189,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585291989,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585294314,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585297245,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585314509,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585725385,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585863938,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585890378,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585937233,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586055397,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586080669,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586083221,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586099778,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586223870,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586275418,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586308209,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586355415,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq"
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
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579966649,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583995060,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_keep_suspended",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584024938,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584103547,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584153950,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584322187,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584331664,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584337818,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584392891,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584766525,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585115561,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585484637,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585497915,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585507835,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585629189,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585714013,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585715253,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585716461,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585720261,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585722554,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585725485,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585742861,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586158793,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586303802,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586330940,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586379057,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586499845,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586525133,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586527701,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586544178,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586687150,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586738778,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586771700,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586820199,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq"
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
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580014243,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584189508,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_keep_suspended",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_enable_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584219817,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584305035,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584371300,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584542973,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584552400,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584558650,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584614891,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584994878,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585345225,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585707196,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:wakeup_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585728621,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585734384,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585752641,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585873557,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585960036,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585961269,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585962484,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585966469,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585968593,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585971524,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585988964,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586410215,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586560455,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586588043,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586631909,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586638525,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586764371,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586789100,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586791747,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586814533,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586951486,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587005226,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587044190,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587112373,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq"
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
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580061267,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584278196,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_keep_suspended",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_enable_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584309463,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584355034,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584399771,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584640189,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584650138,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584655946,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584714587,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585099230,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585472457,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585838828,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:wakeup_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585861325,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585867095,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585885457,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586009333,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586096612,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586097845,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586099060,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586102853,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586105108,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586108148,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586125700,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586554002,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586709238,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586737051,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586780981,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586787645,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586921923,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586946236,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586948883,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586969285,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587112366,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587166666,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587204272,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587290629,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:86",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq"
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
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580104872,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584472676,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_adjust_pme",
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_enable_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584504385,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584549954,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584597467,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584840061,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584849563,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584856026,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584914199,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585303822,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585688283,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586075276,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:wakeup_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586098037,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586104102,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586122620,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586253157,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586331966,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586333189,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586334398,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586338277,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586340495,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586343537,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586360846,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586804431,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_may_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586961669,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586992248,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587037429,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587042746,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587096488,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587181547,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587202929,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587209291,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587229671,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587376969,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587431253,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587469508,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587561141,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:73",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580153867,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584607956,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_adjust_pme",
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_enable_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584640321,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584685618,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584735291,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584975789,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584985307,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584991898,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585049911,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585441790,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585829355,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586223468,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:wakeup_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586245557,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586251670,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586271260,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586401365,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586480094,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586481317,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586482542,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586486421,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586488655,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586491697,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586508814,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586956485,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587160677,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587191320,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587237829,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587243146,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587297016,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587381771,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587403217,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587409547,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587429959,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587578857,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587634309,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587672628,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587764485,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580214105,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585285332,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_adjust_pme",
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585324612,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585389579,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585400610,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585672181,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585683131,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585690027,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585753385,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586158797,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586559019,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586989500,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:wakeup_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587014069,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587019195,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587038540,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587176933,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587257678,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587259029,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587260286,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587264453,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587266223,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587269793,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587288782,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587774122,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588010529,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588043479,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588091637,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588097978,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588152328,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588240926,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588265727,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588269355,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588286305,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588440921,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588502053,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588540230,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588610421,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580198377,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585439892,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_adjust_pme",
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585477943,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585546907,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585557301,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585796693,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585805419,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585812158,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585872505,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586276237,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586669835,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587074204,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:wakeup_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587098725,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587103787,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587122108,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587260309,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587325326,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587326133,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587326606,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587330053,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587331695,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587335025,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587349694,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587833226,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588062812,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588092327,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588133589,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588140042,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588192872,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588276686,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588301407,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588304475,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588321329,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588472521,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588530901,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588563670,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588633397,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580203686,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585320036,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_adjust_pme",
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585357783,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585425435,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585435413,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585677381,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585686123,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585692735,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585750265,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586150013,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586554091,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586960495,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:wakeup_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586985061,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586992011,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587148757,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587211998,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587212565,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587213038,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587216501,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587218095,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587221393,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587231870,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587711901,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587944851,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587975113,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588015765,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588022138,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588068728,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588159774,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588184588,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588187723,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588208853,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588354697,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588412677,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588446873,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588518149,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580350390,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585785759,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_adjust_pme",
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585817063,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585890491,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585901045,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586157045,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586166139,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586173129,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586232837,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586651677,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587092011,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587526639,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:wakeup_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587551189,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587558235,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587724693,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587774414,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587774981,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587775454,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587779109,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587780703,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587785329,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588304365,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588555360,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588586809,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588631797,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588638404,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588697432,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588799312,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588824572,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588827707,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588849797,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589016281,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589081237,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589116495,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589191685,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580564725,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586973193,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_adjust_pme",
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587007235,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587086923,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587103455,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587390557,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587401049,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587407952,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587471213,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587919149,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588397100,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588856607,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:wakeup_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588883685,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588889485,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589069029,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589121038,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589121621,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589122158,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589126021,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589127742,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589132609,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589667876,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589690512,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:mdio_bus_phy_suspend",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589964070,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589999159,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590047397,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590054697,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590115624,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590222416,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590247381,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590252187,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590273067,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590454281,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590524197,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590564538,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590653781,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/power/supply/charger-manager.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580824933,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588138521,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_adjust_pme",
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588176253,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588274507,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588295276,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588642365,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588654729,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588662701,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588738509,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589271405,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589822348,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590362655,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:wakeup_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590392453,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590399405,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590599157,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590661598,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590662949,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590664302,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590669093,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590671118,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590676593,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591278580,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591304032,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:mdio_bus_phy_suspend",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591555358,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591595367,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591651733,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591657313,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_poweroff_late",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591727784,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591840640,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591866853,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591872347,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591894360,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592095417,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592173223,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592217498,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592319349,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/power/supply/charger-manager.c",
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
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580908469,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588413899,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_adjust_pme",
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588452285,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588550139,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588571404,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588930301,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588942681,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588950029,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589026685,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589568029,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590128188,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590683151,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:wakeup_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590711941,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590717032,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590940261,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591002510,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591003893,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591005246,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591010037,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591012062,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591017681,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591634388,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591662672,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:mdio_bus_phy_suspend",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591976957,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592017207,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592074373,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592080161,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_poweroff_late",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592151176,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592263568,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592289750,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592295755,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592317425,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592519033,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592596791,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592641899,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592745957,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/power/supply/charger-manager.c",
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
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580998997,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588709211,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_adjust_pme",
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588749247,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588849755,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588871228,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589226909,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589239305,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589246653,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589331101,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589877453,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590464012,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591044607,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:wakeup_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591073909,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591079192,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591284069,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591346526,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591347877,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591349230,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591354021,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591356046,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591361681,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592374980,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592404960,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:mdio_bus_phy_suspend",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592716943,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592757479,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592814645,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592820593,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_poweroff_late",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592891800,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593004656,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593031062,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_root_hub_state_changes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593037067,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593058817,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593263625,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593341495,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593386891,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593493909,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:82",
      "file": "drivers/power/supply/charger-manager.c",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491376536,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496847212,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_adjust_pme",
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496887796,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496937268,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496996108,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497389232,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497394272,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498154008,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/soc/xilinx/zynqmp_pm_domains.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498548188,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499033012,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:wakeup_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499064912,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499071580,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499094004,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499250192,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499262780,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/stmpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/stmpe.c:stmpe_resume",
        "drivers/mfd/stmpe.c:stmpe_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499267704,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/tc3589x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tc3589x.c:tc3589x_resume",
        "drivers/mfd/tc3589x.c:tc3589x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499350680,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499354848,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max77686.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77686.c:max77686_resume",
        "drivers/mfd/max77686.c:max77686_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499355576,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499356800,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499360472,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499363072,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499366656,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499388560,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499393372,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/as3722.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/as3722.c:as3722_i2c_resume",
        "drivers/mfd/as3722.c:as3722_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499942644,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500010760,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500236964,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500275632,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500335168,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500341760,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500349832,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/phy/phy-mxs-usb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_system_resume",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_system_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500413892,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500505192,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/ehci-orion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500533828,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500561208,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500826672,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/rtc/rtc-sun6i.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_resume",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500830740,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/rtc/rtc-xgene.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-xgene.c:xgene_rtc_resume",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500961048,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225373980,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 3230044452,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/gpio/gpio-htc-egpio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-htc-egpio.c:egpio_resume",
        "drivers/gpio/gpio-htc-egpio.c:egpio_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3230127296,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_adjust_pme",
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 3230163932,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 3230256128,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 3231190956,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 3231312916,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/tty/serial/omap-serial.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/omap-serial.c:serial_omap_resume",
        "drivers/tty/serial/omap-serial.c:serial_omap_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3231593264,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:wakeup_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3231617868,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3231624504,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 3231646580,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3231755808,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3231779772,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/stmpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/stmpe.c:stmpe_resume",
        "drivers/mfd/stmpe.c:stmpe_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3231783980,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/tc3589x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tc3589x.c:tc3589x_resume",
        "drivers/mfd/tc3589x.c:tc3589x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3231899300,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3231903536,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max77686.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77686.c:max77686_resume",
        "drivers/mfd/max77686.c:max77686_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3231904208,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3231905460,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3231909404,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3231911656,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3231914912,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3231940848,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3231945688,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/as3722.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/as3722.c:as3722_i2c_resume",
        "drivers/mfd/as3722.c:as3722_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3232485444,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232535168,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232712460,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": []
    },
    {
      "addr": 3232746124,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3232794892,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3232800992,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3232808692,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/phy/phy-mxs-usb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_system_resume",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_system_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3232869600,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy"
      ],
      "caller_func": []
    },
    {
      "addr": 3232955908,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/ehci-orion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3232957232,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/ehci-exynos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3232983316,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ],
      "caller_func": []
    },
    {
      "addr": 3232990200,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/ohci-exynos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3233016776,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 3233333912,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/rtc/rtc-omap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-omap.c:omap_rtc_resume",
        "drivers/rtc/rtc-omap.c:omap_rtc_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3233341100,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/rtc/rtc-s3c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-s3c.c:s3c_rtc_resume",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3233474540,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 3233962272,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mmc/host/sdhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/sdhci.c:sdhci_suspend_host"
      ],
      "caller_func": []
    },
    {
      "addr": 3234517928,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "sound/soc/soc-jack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/soc/soc-jack.c:gpio_handler"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284313664,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290924288,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_adjust_pme",
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290974832,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291772752,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292201824,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:wakeup_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292239652,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292248812,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292277352,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292433584,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292449248,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/stmpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/stmpe.c:stmpe_resume",
        "drivers/mfd/stmpe.c:stmpe_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292455128,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/tc3589x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tc3589x.c:tc3589x_resume",
        "drivers/mfd/tc3589x.c:tc3589x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292578408,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292584088,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max77686.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77686.c:max77686_resume",
        "drivers/mfd/max77686.c:max77686_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292585008,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292586760,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292592016,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292595208,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292599900,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292626968,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292632248,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/as3722.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/as3722.c:as3722_i2c_resume",
        "drivers/mfd/as3722.c:as3722_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293264488,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055293531956,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293575752,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293644376,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293654800,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293754148,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293916556,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293954640,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294165744,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294421888,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271864352,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:163",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275551382,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:163",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_adjust_pme",
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_prepare_to_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275659928,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:163",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276165778,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:163",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276419056,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:163",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276520716,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:163",
      "file": "drivers/mfd/stmpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/stmpe.c:stmpe_resume",
        "drivers/mfd/stmpe.c:stmpe_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276595594,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:163",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276602302,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:163",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276605506,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:163",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277026550,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:163",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277159068,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:163",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277186638,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:163",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277228036,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:163",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277304810,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:163",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277413352,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:163",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277438826,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:163",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277720536,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:163",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580123067,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584560116,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_adjust_pme",
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_enable_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584636098,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584684091,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584923357,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584929963,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584936170,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585204318,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585590347,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585983676,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:wakeup_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586005765,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586014454,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586034508,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586713493,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586866757,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586897400,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586943909,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586949226,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587003096,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587087851,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587109297,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587115627,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587136039,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587269433,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587356388,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580068363,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584488276,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_adjust_pme",
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_enable_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584520609,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584565906,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584614155,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584829229,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584838699,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584844970,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584896855,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585156526,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585455195,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585832940,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:wakeup_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585854885,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585860998,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585880524,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586581797,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586806377,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586838520,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586885077,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586890378,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587040169,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587124628,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580114139,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584558116,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_adjust_pme",
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_enable_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584590481,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584635778,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584685451,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584927373,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584936891,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584943482,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585001495,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585392190,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585779755,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586173484,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:wakeup_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586195573,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586201686,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586221276,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586349333,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586428062,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586429285,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586430510,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586434389,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586436623,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586439665,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586456782,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586911045,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587115237,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587145880,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587192389,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587197706,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587251576,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587336331,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587357777,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587364107,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587384519,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587530105,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587585557,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587623876,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587720629,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq"
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
  "name": "device_may_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580165931,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584665860,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_check_d3cold",
        "drivers/pci/pci.c:pci_dev_adjust_pme",
        "drivers/pci/pci.c:pci_dev_need_resume",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_enable_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584698529,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584743474,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584791611,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_check_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585033517,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_disable_wakeup_devices",
        "drivers/acpi/wakeup.c:acpi_enable_wakeup_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585043067,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_pm_get_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585049658,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_write_wakeup_device",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show",
        "drivers/acpi/proc.c:acpi_system_wakeup_device_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585107671,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585499534,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585882059,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586282172,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:wakeup_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586304149,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeirq.c:dev_pm_disarm_wake_irq",
        "drivers/base/power/wakeirq.c:dev_pm_arm_wake_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586308438,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:pm_dev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586330700,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586461013,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_resume",
        "drivers/mfd/88pm860x-core.c:pm860x_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586539742,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_resume",
        "drivers/mfd/max14577.c:max14577_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586540965,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_resume",
        "drivers/mfd/max77693.c:max77693_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586542190,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_resume",
        "drivers/mfd/max77843.c:max77843_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586546069,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_resume",
        "drivers/mfd/max8925-i2c.c:max8925_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586548303,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_resume",
        "drivers/mfd/max8997.c:max8997_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586551345,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_resume",
        "drivers/mfd/max8998.c:max8998_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586568462,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_resume",
        "drivers/mfd/sec-core.c:sec_pmic_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587017429,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587220262,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:rh_call_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587252952,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587299461,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587304778,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587358344,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587442811,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587463489,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587470459,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587486199,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:suspend_rh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587641337,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_pm_resume",
        "drivers/input/serio/i8042.c:i8042_pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587696453,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587734084,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587833685,
      "name": "device_may_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:77",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
bool device_may_wakeup(struct device * dev)
```
</details>
</li>
</ul>
