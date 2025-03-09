# Function: <code>dev_pm_skip_resume</code>

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
bool dev_pm_skip_resume(struct device * dev)
```

```json
{
  "name": "dev_pm_skip_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587020887,
      "name": "dev_pm_skip_resume",
      "external": true,
      "loc": "drivers/base/power/main.c:574",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_resume_early",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587023600,
      "name": "dev_pm_skip_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool dev_pm_skip_resume(struct device * dev)
```

```json
{
  "name": "dev_pm_skip_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587105479,
      "name": "dev_pm_skip_resume",
      "external": true,
      "loc": "drivers/base/power/main.c:573",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_resume_early",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587108128,
      "name": "dev_pm_skip_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool dev_pm_skip_resume(struct device * dev)
```

```json
{
  "name": "dev_pm_skip_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586989767,
      "name": "dev_pm_skip_resume",
      "external": true,
      "loc": "drivers/base/power/main.c:574",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_resume_early",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586994480,
      "name": "dev_pm_skip_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool dev_pm_skip_resume(struct device * dev)
```

```json
{
  "name": "dev_pm_skip_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587556007,
      "name": "dev_pm_skip_resume",
      "external": true,
      "loc": "drivers/base/power/main.c:571",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_resume_early",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_resume",
        "drivers/acpi/device_pm.c:acpi_subsys_resume",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587560624,
      "name": "dev_pm_skip_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool dev_pm_skip_resume(struct device * dev)
```

```json
{
  "name": "dev_pm_skip_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588891363,
      "name": "dev_pm_skip_resume",
      "external": true,
      "loc": "drivers/base/power/main.c:570",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_resume_early",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_resume",
        "drivers/acpi/device_pm.c:acpi_subsys_resume",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588894112,
      "name": "dev_pm_skip_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool dev_pm_skip_resume(struct device * dev)
```

```json
{
  "name": "dev_pm_skip_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590401539,
      "name": "dev_pm_skip_resume",
      "external": true,
      "loc": "drivers/base/power/main.c:570",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_resume_early",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_resume",
        "drivers/acpi/device_pm.c:acpi_subsys_resume",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590404320,
      "name": "dev_pm_skip_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool dev_pm_skip_resume(struct device * dev)
```

```json
{
  "name": "dev_pm_skip_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590721043,
      "name": "dev_pm_skip_resume",
      "external": true,
      "loc": "drivers/base/power/main.c:570",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_resume_early",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_resume",
        "drivers/acpi/device_pm.c:acpi_subsys_resume",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590723872,
      "name": "dev_pm_skip_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool dev_pm_skip_resume(struct device * dev)
```

```json
{
  "name": "dev_pm_skip_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591083269,
      "name": "dev_pm_skip_resume",
      "external": true,
      "loc": "drivers/base/power/main.c:570",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_noirq"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_resume_early",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/acpi/device_pm.c:acpi_subsys_resume",
        "drivers/acpi/device_pm.c:acpi_subsys_resume",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591086192,
      "name": "dev_pm_skip_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool dev_pm_skip_resume(struct device * dev)
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
