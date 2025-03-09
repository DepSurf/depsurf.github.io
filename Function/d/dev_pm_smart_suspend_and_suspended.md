# Function: <code>dev_pm_smart_suspend_and_suspended</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool dev_pm_smart_suspend_and_suspended(struct device * dev)
```

```json
{
  "name": "dev_pm_smart_suspend_and_suspended",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585499584,
      "name": "dev_pm_smart_suspend_and_suspended",
      "external": true,
      "loc": "drivers/base/power/main.c:1941",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_late",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_thaw_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_freeze_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_freeze_late",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585499584,
      "name": "dev_pm_smart_suspend_and_suspended",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool dev_pm_smart_suspend_and_suspended(struct device * dev)
```

```json
{
  "name": "dev_pm_smart_suspend_and_suspended",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585734139,
      "name": "dev_pm_smart_suspend_and_suspended",
      "external": true,
      "loc": "drivers/base/power/main.c:2117",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_late",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_thaw_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_freeze_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_freeze_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585743744,
      "name": "dev_pm_smart_suspend_and_suspended",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool dev_pm_smart_suspend_and_suspended(struct device * dev)
```

```json
{
  "name": "dev_pm_smart_suspend_and_suspended",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585866843,
      "name": "dev_pm_smart_suspend_and_suspended",
      "external": true,
      "loc": "drivers/base/power/main.c:2123",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_late",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_thaw_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_freeze_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_freeze_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585876480,
      "name": "dev_pm_smart_suspend_and_suspended",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool dev_pm_smart_suspend_and_suspended(struct device * dev)
```

```json
{
  "name": "dev_pm_smart_suspend_and_suspended",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586103863,
      "name": "dev_pm_smart_suspend_and_suspended",
      "external": true,
      "loc": "drivers/base/power/main.c:2111",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586113728,
      "name": "dev_pm_smart_suspend_and_suspended",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool dev_pm_smart_suspend_and_suspended(struct device * dev)
```

```json
{
  "name": "dev_pm_smart_suspend_and_suspended",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586251431,
      "name": "dev_pm_smart_suspend_and_suspended",
      "external": true,
      "loc": "drivers/base/power/main.c:2132",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586261152,
      "name": "dev_pm_smart_suspend_and_suspended",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool dev_pm_smart_suspend_and_suspended(struct device * dev)
```

```json
{
  "name": "dev_pm_smart_suspend_and_suspended",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499071320,
      "name": "dev_pm_smart_suspend_and_suspended",
      "external": true,
      "loc": "drivers/base/power/main.c:2132",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499082368,
      "name": "dev_pm_smart_suspend_and_suspended",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool dev_pm_smart_suspend_and_suspended(struct device * dev)
```

```json
{
  "name": "dev_pm_smart_suspend_and_suspended",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231623900,
      "name": "dev_pm_smart_suspend_and_suspended",
      "external": true,
      "loc": "drivers/base/power/main.c:2132",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231635536,
      "name": "dev_pm_smart_suspend_and_suspended",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
bool dev_pm_smart_suspend_and_suspended(struct device * dev)
```

```json
{
  "name": "dev_pm_smart_suspend_and_suspended",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292248448,
      "name": "dev_pm_smart_suspend_and_suspended",
      "external": true,
      "loc": "drivers/base/power/main.c:2132",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292263600,
      "name": "dev_pm_smart_suspend_and_suspended",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool dev_pm_smart_suspend_and_suspended(struct device * dev)
```

```json
{
  "name": "dev_pm_smart_suspend_and_suspended",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586014119,
      "name": "dev_pm_smart_suspend_and_suspended",
      "external": true,
      "loc": "drivers/base/power/main.c:2132",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586024480,
      "name": "dev_pm_smart_suspend_and_suspended",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool dev_pm_smart_suspend_and_suspended(struct device * dev)
```

```json
{
  "name": "dev_pm_smart_suspend_and_suspended",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585860759,
      "name": "dev_pm_smart_suspend_and_suspended",
      "external": true,
      "loc": "drivers/base/power/main.c:2132",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585870432,
      "name": "dev_pm_smart_suspend_and_suspended",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool dev_pm_smart_suspend_and_suspended(struct device * dev)
```

```json
{
  "name": "dev_pm_smart_suspend_and_suspended",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586201447,
      "name": "dev_pm_smart_suspend_and_suspended",
      "external": true,
      "loc": "drivers/base/power/main.c:2132",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586211168,
      "name": "dev_pm_smart_suspend_and_suspended",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool dev_pm_smart_suspend_and_suspended(struct device * dev)
```

```json
{
  "name": "dev_pm_smart_suspend_and_suspended",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586311351,
      "name": "dev_pm_smart_suspend_and_suspended",
      "external": true,
      "loc": "drivers/base/power/main.c:2132",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586320240,
      "name": "dev_pm_smart_suspend_and_suspended",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
bool dev_pm_smart_suspend_and_suspended(struct device * dev)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
bool dev_pm_smart_suspend_and_suspended(struct device * dev)
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
bool dev_pm_smart_suspend_and_suspended(struct device * dev)
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
