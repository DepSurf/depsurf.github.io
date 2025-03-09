# Function: <code>pm_wakeup_dev_event</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585078960,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:793",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/device_pm.c:acpi_pm_wakeup_event",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/mmc/core/core.c:_mmc_detect_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585078960,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585502304,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:794",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/device_pm.c:acpi_pm_wakeup_event",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/mmc/core/core.c:_mmc_detect_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585502304,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585747280,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:793",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/device_pm.c:acpi_pm_wakeup_event",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/mmc/core/core.c:_mmc_detect_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585747280,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585880048,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:799",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/device_pm.c:acpi_pm_wakeup_event",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/input/serio/i8042.c:i8042_interrupt",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/mmc/core/core.c:_mmc_detect_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585880048,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586116496,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:783",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/device_pm.c:acpi_pm_wakeup_event",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/mmc/core/core.c:_mmc_detect_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586116496,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586264304,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:803",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/device_pm.c:acpi_pm_wakeup_event",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/mmc/core/core.c:_mmc_detect_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586264304,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587033904,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:862",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/device_pm.c:acpi_pm_wakeup_event",
        "drivers/usb/core/hub.c:report_wakeup_requests",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/rtc/rtc-cmos.c:rtc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033904,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587117360,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:862",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/device_pm.c:acpi_pm_wakeup_event",
        "drivers/usb/core/hub.c:report_wakeup_requests",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/rtc/rtc-cmos.c:rtc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587117360,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587003136,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:863",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/device_pm.c:acpi_pm_wakeup_event",
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/rtc/rtc-cmos.c:rtc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587003136,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587569344,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:864",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/acpi/sleep.c:acpi_pm_finish",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/device_pm.c:acpi_pm_wakeup_event",
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/rtc/rtc-cmos.c:rtc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587569344,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588904640,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:864",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/acpi/sleep.c:acpi_pm_finish",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/device_pm.c:acpi_pm_wakeup_event",
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/rtc/rtc-cmos.c:rtc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588904640,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590416352,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:834",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/acpi/sleep.c:acpi_pm_finish",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/device_pm.c:acpi_pm_wakeup_event",
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/rtc/rtc-cmos.c:rtc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590416352,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590735872,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:829",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/acpi/sleep.c:acpi_pm_finish",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/device_pm.c:acpi_pm_wakeup_event",
        "drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq",
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/rtc/rtc-cmos.c:rtc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590735872,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591097840,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:829",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/acpi/sleep.c:acpi_pm_finish",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/device_pm.c:acpi_pm_wakeup_event",
        "drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq",
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte",
        "drivers/rtc/rtc-cmos.c:rtc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591097840,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499087048,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:803",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/device_pm.c:acpi_pm_wakeup_event",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499087048,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231638808,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:803",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "sound/soc/soc-jack.c:gpio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231638808,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292268288,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:803",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292268288,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
  "name": "pm_wakeup_dev_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_wakeup_dev_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:181",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pm_wakeup_dev_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:181",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pm_wakeup_dev_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:181",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pm_wakeup_dev_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:181",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pm_wakeup_dev_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:181",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pm_wakeup_dev_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:181",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pm_wakeup_dev_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:181",
      "file": "drivers/mmc/core/core.c",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586027616,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:803",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/device_pm.c:acpi_pm_wakeup_event",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/mmc/core/core.c:_mmc_detect_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586027616,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585873584,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:803",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/device_pm.c:acpi_pm_wakeup_event",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/rtc/rtc-cmos.c:rtc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585873584,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586214320,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:803",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/device_pm.c:acpi_pm_wakeup_event",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/mmc/core/core.c:_mmc_detect_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586214320,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```

```json
{
  "name": "pm_wakeup_dev_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586323456,
      "name": "pm_wakeup_dev_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:803",
      "file": "drivers/base/power/wakeup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/device_pm.c:acpi_pm_wakeup_event",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/mmc/core/core.c:_mmc_detect_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586323456,
      "name": "pm_wakeup_dev_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
```
</details>
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
void pm_wakeup_dev_event(struct device * dev, unsigned int msec, bool hard)
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
