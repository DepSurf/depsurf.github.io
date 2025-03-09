# Function: <code>pm_wakeup_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pm_wakeup_event(struct device * dev, unsigned int msec)
```

```json
{
  "name": "pm_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584465760,
      "name": "pm_wakeup_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:794",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_wakeup",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/button.c:acpi_lid_send_state",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/mmc/core/core.c:_mmc_detect_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584465760,
      "name": "pm_wakeup_event",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void pm_wakeup_event(struct device * dev, unsigned int msec)
```

```json
{
  "name": "pm_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584802144,
      "name": "pm_wakeup_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:792",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/mmc/core/core.c:_mmc_detect_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584802144,
      "name": "pm_wakeup_event",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void pm_wakeup_event(struct device * dev, unsigned int msec)
```

```json
{
  "name": "pm_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584994144,
      "name": "pm_wakeup_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:792",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func",
        "drivers/acpi/button.c:acpi_button_notify",
        "drivers/acpi/button.c:acpi_lid_notify_state",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/rtc/rtc-cmos.c:rtc_handler",
        "drivers/mmc/core/core.c:_mmc_detect_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584994144,
      "name": "pm_wakeup_event",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583752669,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:211",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583842424,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:211",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583891087,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:211",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584057143,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:211",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584063379,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:211",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585061171,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:211",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585066910,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:211",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585837424,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:211",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586648010,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:211",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:_mmc_detect_change"
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
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584011709,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:211",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584105140,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:211",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584153823,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:211",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584324151,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:211",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584332531,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:211",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585484003,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:211",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585489742,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:211",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586276800,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:211",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587130666,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:211",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:_mmc_detect_change"
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
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584207312,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584305744,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584371151,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584547215,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584553283,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585727923,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585734818,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586534357,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586551275,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587430538,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:_mmc_detect_change"
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
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584295120,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584354879,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584401408,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584644431,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584651027,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585861059,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585867529,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586681249,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586700123,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587109736,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/input/serio/i8042.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/i8042.c:i8042_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587611402,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:218",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:_mmc_detect_change"
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
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584489484,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:196",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584549785,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:196",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584597053,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:196",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584844222,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:196",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584850516,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:196",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586097783,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:196",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586104413,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:196",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586934801,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:196",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586954907,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:196",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587421587,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:196",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587888954,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:196",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:_mmc_detect_change"
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
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584625068,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584685449,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584734877,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584979964,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584986260,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586245303,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586251981,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587133233,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587153563,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587624643,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588108186,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:_mmc_detect_change"
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
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580218498,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:200",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585308044,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:200",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585388864,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:200",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585400271,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:200",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585676835,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:200",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585683620,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:200",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587013162,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:200",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587968966,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:200",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:report_wakeup_requests",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588003995,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:200",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588493027,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:200",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588965237,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:200",
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
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580202615,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585464764,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585546192,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585556959,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591431570,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585806004,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587097802,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588028726,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:report_wakeup_requests",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588057355,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588522291,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
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
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580207911,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585344892,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585424448,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585435279,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591372773,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585686708,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586984138,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587916690,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587939739,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588403763,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
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
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580355271,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585804012,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585889456,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585900767,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592407241,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_pm_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586166724,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587550490,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588526623,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588550123,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589072656,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
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
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580569807,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586992307,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587086511,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587099088,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594272853,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_pm_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587400835,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588882692,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589934867,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589959687,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590508584,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:210",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580830175,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588159795,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588273939,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588290352,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588643828,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_pm_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588654483,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590391280,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591516483,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591548359,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592155784,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
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
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580913727,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588435315,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588549573,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588566184,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588931796,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_pm_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588942435,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590165445,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590710768,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591937872,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591969975,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592579300,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:202",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte"
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
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581004314,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:212",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588732103,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:212",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588849189,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:212",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588866008,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:212",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589228404,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:212",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_pm_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589239059,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:212",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590503273,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:212",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591072624,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:212",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592678304,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:212",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592709815,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:212",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593324036,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:212",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496869364,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496937968,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496997172,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497394880,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499063524,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499072116,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500209488,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500235704,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500779400,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501359564,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
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
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230147124,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 3230257960,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 3231616884,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231624944,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3232688708,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 3232708472,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 3233290440,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 3233851176,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234517956,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
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
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290951220,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292238464,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292249452,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293497628,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293522080,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294231700,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294914148,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
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
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584577228,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584635929,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584683677,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584924655,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584930932,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586005511,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586014965,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586839313,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586859643,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587317459,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587729754,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:_mmc_detect_change"
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
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584505388,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584565737,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584614801,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584833366,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584839652,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585854631,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585861309,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586781073,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586801083,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587085827,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
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
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584575228,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584635609,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584685037,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584931548,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584937844,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586195319,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586201997,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587087793,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587108123,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587575891,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588062714,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:_mmc_detect_change"
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
  "name": "pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584682972,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/pci.c:pci_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584743305,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev",
        "drivers/pci/pci-acpi.c:pci_acpi_wake_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584793184,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_walk_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585037724,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585044020,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_pm_notify_work_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586303895,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/base/power/wakeirq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586308749,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587194945,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_resume",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_wakeup_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587215627,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_resume_root_hub"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587687459,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/input/keyboard/atkbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588180250,
      "name": "pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/core.c:_mmc_detect_change"
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
void pm_wakeup_event(struct device * dev, unsigned int msec)
```
</details>
</li>
</ul>
