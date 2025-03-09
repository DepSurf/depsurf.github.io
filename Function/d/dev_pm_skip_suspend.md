# Function: <code>dev_pm_skip_suspend</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dev_pm_skip_suspend(struct device * dev)
```

```json
{
  "name": "dev_pm_skip_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587018094,
      "name": "dev_pm_skip_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:2009",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587029184,
      "name": "dev_pm_skip_suspend",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dev_pm_skip_suspend(struct device * dev)
```

```json
{
  "name": "dev_pm_skip_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587102718,
      "name": "dev_pm_skip_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:2008",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587113424,
      "name": "dev_pm_skip_suspend",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dev_pm_skip_suspend(struct device * dev)
```

```json
{
  "name": "dev_pm_skip_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586993314,
      "name": "dev_pm_skip_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:2009",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586999728,
      "name": "dev_pm_skip_suspend",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dev_pm_skip_suspend(struct device * dev)
```

```json
{
  "name": "dev_pm_skip_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587559506,
      "name": "dev_pm_skip_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:2037",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587565968,
      "name": "dev_pm_skip_suspend",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dev_pm_skip_suspend(struct device * dev)
```

```json
{
  "name": "dev_pm_skip_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588887544,
      "name": "dev_pm_skip_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:2035",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588900000,
      "name": "dev_pm_skip_suspend",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dev_pm_skip_suspend(struct device * dev)
```

```json
{
  "name": "dev_pm_skip_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590396936,
      "name": "dev_pm_skip_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:2035",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590410880,
      "name": "dev_pm_skip_suspend",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dev_pm_skip_suspend(struct device * dev)
```

```json
{
  "name": "dev_pm_skip_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590720296,
      "name": "dev_pm_skip_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:2035",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590730448,
      "name": "dev_pm_skip_suspend",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dev_pm_skip_suspend(struct device * dev)
```

```json
{
  "name": "dev_pm_skip_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591081672,
      "name": "dev_pm_skip_suspend",
      "external": true,
      "loc": "drivers/base/power/main.c:2034",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591092368,
      "name": "dev_pm_skip_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool dev_pm_skip_suspend(struct device * dev)
```
</details>
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
