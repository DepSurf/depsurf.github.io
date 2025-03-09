# Function: <code>acpi_device_set_power</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583550921,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:149",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/fan.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583550921,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583872348,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:150",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/fan.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872348,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584011400,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:150",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/fan.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584011400,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584063552,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:151",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_resume_early",
        "drivers/acpi/device_pm.c:acpi_dev_runtime_resume",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/fan.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584063552,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 687
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
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584333056,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:151",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/fan.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333056,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 886
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
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584553728,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:151",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/fan.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584553728,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 895
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
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584651472,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:152",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/fan.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584651472,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 904
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:160",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/fan.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584854946,
      "name": "acpi_device_set_power.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071584850960,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:160",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/fan.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584990834,
      "name": "acpi_device_set_power.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071584986704,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:160",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/fan.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585688965,
      "name": "acpi_device_set_power.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071585684976,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 871
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:160",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/fan.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591431738,
      "name": "acpi_device_set_power.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071585807280,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:160",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/fan.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591372899,
      "name": "acpi_device_set_power.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071585687616,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 797
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:160",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/fan.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592407542,
      "name": "acpi_device_set_power.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071586167776,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
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
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587402272,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:160",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_power_up_if_adr_present",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/fan_core.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587402272,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1089
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
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588656464,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:162",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_power_up_if_adr_present",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim_one",
        "drivers/acpi/fan_core.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588656464,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1132
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
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588944416,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:162",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_power_up_if_adr_present",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim_one",
        "drivers/acpi/fan_core.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588944416,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1140
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
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589241040,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:162",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_power_up_if_adr_present",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim_one",
        "drivers/acpi/fan_core.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589241040,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1140
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
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497395408,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:160",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/fan.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497395408,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:160",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584935106,
      "name": "acpi_device_set_power.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071584931376,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:160",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584843906,
      "name": "acpi_device_set_power.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071584840096,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:160",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/fan.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584942418,
      "name": "acpi_device_set_power.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071584938288,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int acpi_device_set_power(struct acpi_device * device, int state)
```

```json
{
  "name": "acpi_device_set_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_device_set_power",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:160",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_device_update_power",
        "drivers/acpi/device_pm.c:acpi_bus_set_power",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/fan.c:fan_set_cur_state",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585048594,
      "name": "acpi_device_set_power.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071585044464,
      "name": "acpi_device_set_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_device_set_power(struct acpi_device * device, int state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_device_set_power(struct acpi_device * device, int state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_device_set_power(struct acpi_device * device, int state)
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
