# Function: <code>device_init_wakeup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584466240,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:438",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/battery.c:acpi_battery_remove",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/i2c/i2c-core.c:i2c_device_remove",
        "drivers/i2c/i2c-core.c:i2c_device_probe",
        "drivers/i2c/i2c-core.c:i2c_device_probe",
        "drivers/power/power_supply_core.c:power_supply_unregister",
        "drivers/power/power_supply_core.c:__power_supply_register",
        "drivers/power/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584466240,
      "name": "device_init_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584802752,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:436",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/battery.c:acpi_battery_remove",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/i2c/i2c-core.c:i2c_device_remove",
        "drivers/i2c/i2c-core.c:i2c_device_probe",
        "drivers/i2c/i2c-core.c:i2c_device_probe",
        "drivers/power/power_supply_core.c:power_supply_unregister",
        "drivers/power/power_supply_core.c:__power_supply_register",
        "drivers/power/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584802752,
      "name": "device_init_wakeup",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584994752,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:436",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/battery.c:acpi_battery_remove",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core.c:i2c_device_remove",
        "drivers/i2c/i2c-core.c:i2c_device_probe",
        "drivers/i2c/i2c-core.c:i2c_device_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584994752,
      "name": "device_init_wakeup",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585079728,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:438",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/battery.c:acpi_battery_remove",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585079728,
      "name": "device_init_wakeup",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585503072,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:440",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/battery.c:acpi_battery_remove",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585503072,
      "name": "device_init_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585747904,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:444",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/battery.c:acpi_battery_remove",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585747904,
      "name": "device_init_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585880624,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:450",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/battery.c:acpi_battery_remove",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585880624,
      "name": "device_init_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586117712,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:434",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/battery.c:acpi_battery_remove",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586117712,
      "name": "device_init_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586265200,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:454",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/battery.c:acpi_battery_remove",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586265200,
      "name": "device_init_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587033280,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:513",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/acpi/scan.c:acpi_bus_scan_fixed",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/battery.c:acpi_battery_remove",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033280,
      "name": "device_init_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587116736,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:513",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/acpi/scan.c:acpi_bus_scan_fixed",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/battery.c:acpi_battery_remove",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587116736,
      "name": "device_init_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587003648,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:513",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/battery.c:acpi_battery_remove",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587003648,
      "name": "device_init_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587569952,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:514",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/battery.c:acpi_battery_remove",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587569952,
      "name": "device_init_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588905024,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:514",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/acpi/scan.c:acpi_bus_scan_fixed",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/battery.c:acpi_battery_remove",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588905024,
      "name": "device_init_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
  "name": "device_init_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580825027,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588689207,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/acpi/scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_scan_fixed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589136213,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589192169,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/acpi/battery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/acpi/battery.c:acpi_battery_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590662196,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590664886,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590669708,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590671637,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590677011,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590684339,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591528727,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_new_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591871925,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/usb/host/ohci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592219462,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592232524,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592310257,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592325245,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
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
  "name": "device_init_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580908563,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588977127,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/acpi/scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_scan_fixed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589428610,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589486313,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/acpi/battery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/acpi/battery.c:acpi_battery_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591003108,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591005830,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591010652,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591012581,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591018103,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591025395,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591950583,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_new_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592295333,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/usb/host/ohci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592643853,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592657596,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592736705,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592751957,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:223",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
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
  "name": "device_init_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580999091,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:233",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589274759,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:233",
      "file": "drivers/acpi/scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_scan_fixed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589736420,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:233",
      "file": "drivers/acpi/button.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/button.c:acpi_button_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589792632,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:233",
      "file": "drivers/acpi/battery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/battery.c:acpi_battery_remove",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/acpi/battery.c:acpi_battery_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591347112,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:233",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591349814,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:233",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591354636,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:233",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591356544,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:233",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591362082,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:233",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591369443,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:233",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592690407,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:233",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_new_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593036645,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:233",
      "file": "drivers/usb/host/ohci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593388956,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:233",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_do_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593402764,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:233",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593484657,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:233",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593499870,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:233",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499088592,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:454",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/battery.c:acpi_battery_remove",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3722.c:as3722_i2c_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/rtc/rtc-mv.c:mv_rtc_remove",
        "drivers/rtc/rtc-mv.c:mv_rtc_probe",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_remove",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499088592,
      "name": "device_init_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231640376,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:454",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-htc-egpio.c:egpio_probe",
        "drivers/tty/serial/omap-serial.c:serial_omap_remove",
        "drivers/tty/serial/omap-serial.c:serial_omap_probe",
        "drivers/tty/serial/omap-serial.c:serial_omap_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3722.c:as3722_i2c_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/usb/musb/musb_core.c:musb_remove",
        "drivers/usb/musb/musb_core.c:musb_init_controller",
        "drivers/usb/musb/musb_core.c:musb_init_controller",
        "drivers/rtc/rtc-mv.c:mv_rtc_remove",
        "drivers/rtc/rtc-mv.c:mv_rtc_probe",
        "drivers/rtc/rtc-omap.c:omap_rtc_remove",
        "drivers/rtc/rtc-omap.c:omap_rtc_probe",
        "drivers/rtc/rtc-omap.c:omap_rtc_probe",
        "drivers/rtc/rtc-pl031.c:pl031_probe",
        "drivers/rtc/rtc-pl031.c:pl031_remove",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_probe",
        "drivers/rtc/rtc-twl.c:twl_rtc_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_remove",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231640376,
      "name": "device_init_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292270304,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:454",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3722.c:as3722_i2c_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292270304,
      "name": "device_init_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276516796,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:156",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276563640,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:156",
      "file": "drivers/mfd/twl-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl-core.c:add_numbered_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276592538,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:156",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276597190,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:156",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276600416,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:156",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276602778,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:156",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276605874,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:156",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276615510,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:156",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276623736,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:156",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276627232,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:156",
      "file": "drivers/mfd/as3722.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/as3722.c:as3722_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277136030,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:156",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_new_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277415652,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:156",
      "file": "drivers/usb/host/ohci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277640516,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:156",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277713230,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:156",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277729902,
      "name": "device_init_wakeup",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:156",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586028448,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:454",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586028448,
      "name": "device_init_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585874464,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:454",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585874464,
      "name": "device_init_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586215216,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:454",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/battery.c:acpi_battery_remove",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586215216,
      "name": "device_init_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```

```json
{
  "name": "device_init_wakeup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586324256,
      "name": "device_init_wakeup",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:454",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/battery.c:acpi_battery_remove",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/twl-core.c:add_numbered_child",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586324256,
      "name": "device_init_wakeup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int device_init_wakeup(struct device * dev, bool enable)
```
</details>
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
