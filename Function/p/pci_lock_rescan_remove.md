# Function: <code>pci_lock_rescan_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583236176,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:2376",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_bus_rescan_store",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236176,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583545264,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:2416",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:dev_bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583545264,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583681728,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:2494",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:dev_bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681728,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583722448,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:2641",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:dev_bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583722448,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583978416,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:2868",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:dev_bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583978416,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584172272,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3085",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:dev_bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pcie/err.c:pcie_do_fatal_recovery",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172272,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584260352,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3211",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:dev_bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584260352,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584454704,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3435",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:dev_bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:rescan_store",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584454704,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584590032,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3169",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:rescan_store",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584590032,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585266976,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3221",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:rescan_store",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585266976,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585424496,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3229",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:rescan_store",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585424496,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585304704,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3273",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:rescan_store",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585304704,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585761840,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3315",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:rescan_store",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585761840,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586947024,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3286",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:rescan_store",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586947024,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588105840,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3296",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:rescan_store",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/platform/x86/p2sb.c:p2sb_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588105840,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588380448,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3310",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:rescan_store",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/platform/x86/p2sb.c:p2sb_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588380448,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588676912,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3359",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:rescan_store",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588676912,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496829216,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3169",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:rescan_store",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/pci/controller/pci-host-common.c:pci_host_common_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496829216,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230109216,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3169",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:rescan_store",
        "drivers/pci/controller/pci-host-common.c:pci_host_common_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230109216,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290901616,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3169",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/eeh_driver.c:eeh_handle_special_event",
        "arch/powerpc/kernel/eeh_driver.c:eeh_handle_normal_event",
        "arch/powerpc/kernel/eeh_driver.c:eeh_reset_device",
        "arch/powerpc/kernel/eeh_driver.c:eeh_reset_device",
        "arch/powerpc/kernel/eeh_driver.c:eeh_rmv_device",
        "arch/powerpc/kernel/eeh_driver.c:eeh_pe_report",
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:rescan_store",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/controller/pci-host-common.c:pci_host_common_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290901616,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275535448,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3169",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:rescan_store",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/controller/pci-host-common.c:pci_host_common_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275535448,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584542192,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3169",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:rescan_store",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584542192,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584470352,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3169",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:rescan_store",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584470352,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584540192,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3169",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:rescan_store",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584540192,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void pci_lock_rescan_remove()
```

```json
{
  "name": "pci_lock_rescan_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584647936,
      "name": "pci_lock_rescan_remove",
      "external": true,
      "loc": "drivers/pci/probe.c:3169",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked",
        "drivers/pci/pci-sysfs.c:bus_rescan_store",
        "drivers/pci/pci-sysfs.c:dev_rescan_store",
        "drivers/pci/pci-sysfs.c:rescan_store",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge",
        "drivers/acpi/pci_root.c:acpi_pci_root_remove",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584647936,
      "name": "pci_lock_rescan_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
