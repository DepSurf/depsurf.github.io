# Function: <code>device_set_wakeup_capable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584463376,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:410",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hub.c:usb_set_device_state",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/power/charger-manager.c:cm_suspend_noirq",
        "drivers/power/charger-manager.c:cm_suspend_complete",
        "drivers/power/charger-manager.c:charger_manager_probe",
        "drivers/power/charger-manager.c:cm_notify_event",
        "drivers/power/charger-manager.c:cm_notify_event",
        "drivers/power/charger-manager.c:cm_notify_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463376,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584802240,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:408",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hub.c:usb_set_device_state",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/power/charger-manager.c:cm_notify_event",
        "drivers/power/charger-manager.c:cm_notify_event",
        "drivers/power/charger-manager.c:cm_notify_event",
        "drivers/power/charger-manager.c:cm_suspend_complete",
        "drivers/power/charger-manager.c:cm_suspend_noirq",
        "drivers/power/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584802240,
      "name": "device_set_wakeup_capable.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071584802336,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584994240,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:408",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hub.c:usb_set_device_state",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/power/supply/charger-manager.c:cm_notify_event",
        "drivers/power/supply/charger-manager.c:cm_notify_event",
        "drivers/power/supply/charger-manager.c:cm_notify_event",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584994240,
      "name": "device_set_wakeup_capable.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071584994336,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585078096,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:410",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hub.c:usb_set_device_state",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585078096,
      "name": "device_set_wakeup_capable.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071585078208,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585501488,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:410",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hub.c:usb_set_device_state",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585501488,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585746464,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:414",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hub.c:usb_set_device_state",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585746464,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585879232,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:420",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hub.c:usb_set_device_state",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585879232,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586115752,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:404",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hub.c:usb_set_device_state",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/input/serio/i8042.c:i8042_probe",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586118751,
      "name": "device_set_wakeup_capable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071586115680,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586263560,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:424",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hub.c:usb_set_device_state",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/input/serio/i8042.c:i8042_start",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586266217,
      "name": "device_set_wakeup_capable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071586263488,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587030969,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:483",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/input/serio/i8042.c:i8042_start",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:fullbatt_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587034940,
      "name": "device_set_wakeup_capable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587030896,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587114617,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:483",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/input/serio/i8042.c:i8042_start",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591489397,
      "name": "device_set_wakeup_capable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587114544,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587000889,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:483",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/input/serio/i8042.c:i8042_start",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591432412,
      "name": "device_set_wakeup_capable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587000816,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587567129,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:484",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/input/serio/i8042.c:i8042_start",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592492733,
      "name": "device_set_wakeup_capable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587567056,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594362845,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:484",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/input/serio/i8042.c:i8042_start",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594362845,
      "name": "device_set_wakeup_capable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588901824,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590413184,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:484",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_bus_scan_fixed",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/input/serio/i8042.c:i8042_start",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590413184,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590732720,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:479",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_bus_scan_fixed",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:serial_core_add_one_port",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/input/serio/i8042.c:i8042_start",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590732720,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591094640,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:479",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_rtc_add_device",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_bus_scan_fixed",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/battery.c:acpi_battery_remove",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:serial_core_add_one_port",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/input/serio/i8042.c:i8042_start",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_remove",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:charger_manager_probe",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591094640,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499083368,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:424",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hub.c:usb_set_device_state",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499083368,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231638240,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:424",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hub.c:usb_set_device_state",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231638240,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292266720,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:424",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hub.c:usb_set_device_state",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/input/serio/i8042.c:i8042_start",
        "drivers/rtc/rtc-opal.c:opal_rtc_probe",
        "drivers/rtc/rtc-opal.c:opal_rtc_probe",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292266720,
      "name": "device_set_wakeup_capable",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275570868,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pm_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275659696,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276155192,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276516796,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276563644,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/mfd/twl-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl-core.c:add_numbered_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276592538,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/mfd/max14577.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max14577.c:max14577_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276597190,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276600416,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276602778,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/mfd/max8997.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997.c:max8997_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276605874,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/mfd/max8998.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998.c:max8998_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276615510,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276623736,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276627232,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/mfd/as3722.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/as3722.c:as3722_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277136030,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/hub.c:usb_set_device_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277155420,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277259858,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277387514,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277408784,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277415652,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/usb/host/ohci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-pci.c:ohci_quirk_amd756"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277422836,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277640516,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
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
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277726200,
      "name": "device_set_wakeup_capable",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:109",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586026888,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:424",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hub.c:usb_set_device_state",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/input/serio/i8042.c:i8042_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586029465,
      "name": "device_set_wakeup_capable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071586026816,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585872840,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:424",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hub.c:usb_set_device_state",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/input/serio/i8042.c:i8042_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585875481,
      "name": "device_set_wakeup_capable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071585872768,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586213576,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:424",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hub.c:usb_set_device_state",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/input/serio/i8042.c:i8042_start",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586216233,
      "name": "device_set_wakeup_capable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071586213504,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
```

```json
{
  "name": "device_set_wakeup_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586322680,
      "name": "device_set_wakeup_capable",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:424",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/usb/core/hub.c:usb_set_device_state",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ohci-hcd.c:ohci_run",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_init",
        "drivers/input/serio/i8042.c:i8042_start",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_noirq",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586325337,
      "name": "device_set_wakeup_capable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071586322608,
      "name": "device_set_wakeup_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void device_set_wakeup_capable(struct device * dev, bool capable)
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
