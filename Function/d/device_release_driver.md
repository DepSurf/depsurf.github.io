# Function: <code>device_release_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584397120,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:715",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/pnp/card.c:card_probe",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:device_reprobe",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_driver_release_interface",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584397120,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584732224,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:806",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/pnp/card.c:card_probe",
        "drivers/base/bus.c:device_reprobe",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:unbind_store",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_driver_release_interface",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584732224,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584924880,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:872",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/pnp/card.c:card_probe",
        "drivers/base/bus.c:device_reprobe",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:unbind_store",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_driver_release_interface",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584924880,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585009792,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:881",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/bus.c:device_reprobe",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:unbind_store",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_driver_release_interface",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585009792,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585431968,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:921",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/bus.c:device_reprobe",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:unbind_store",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_driver_release_interface",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585431968,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585674944,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:942",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/bus.c:device_reprobe",
        "drivers/base/bus.c:device_reprobe",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:unbind_store",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_driver_release_interface",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585674944,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585805248,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:1026",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/bus.c:device_reprobe",
        "drivers/base/bus.c:device_reprobe",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:unbind_store",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_driver_release_interface",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805248,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586038272,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:1174",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_driver_release_interface",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586038272,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586185792,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:1191",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_driver_release_interface",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586185792,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586943168,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:1165",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_forced_unbind_intf",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586943168,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587028560,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:1213",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_forced_unbind_intf",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587028560,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586912336,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:1228",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_forced_unbind_intf",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586912336,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587474176,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:1257",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_forced_unbind_intf",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587474176,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588800048,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:1267",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_forced_unbind_intf",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588800048,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590296496,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:1295",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/acpi/scan.c:acpi_bus_trim_one",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_forced_unbind_intf",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590296496,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590616560,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:1311",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/acpi/scan.c:acpi_bus_trim_one",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_forced_unbind_intf",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590616560,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590975664,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:1311",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/acpi/scan.c:acpi_bus_trim_one",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_forced_unbind_intf",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590975664,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498984272,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:1191",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/fsl-mc/dprc-driver.c:dprc_scan_objects",
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_driver_release_interface",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498984272,
      "name": "device_release_driver",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231553096,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:1191",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_driver_release_interface",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231553096,
      "name": "device_release_driver",
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292136416,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:1191",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_driver_release_interface",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292136416,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276361568,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:1191",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_driver_release_interface",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276361568,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585946160,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:1191",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/nvme/host/pci.c:nvme_remove_dead_ctrl_work",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_driver_release_interface",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585946160,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585795248,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:1191",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/nvme/host/pci.c:nvme_remove_dead_ctrl_work",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_driver_release_interface",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585795248,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586135808,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:1191",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_driver_release_interface",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586135808,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void device_release_driver(struct device * dev)
```

```json
{
  "name": "device_release_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586244400,
      "name": "device_release_driver",
      "external": true,
      "loc": "drivers/base/dd.c:1191",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/remove.c:pci_stop_bus_device",
        "drivers/acpi/scan.c:acpi_bus_trim",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/net/phy/phy_device.c:phy_detach",
        "drivers/usb/core/driver.c:usb_driver_release_interface",
        "drivers/input/serio/serio.c:serio_disconnect_port",
        "drivers/input/serio/serio.c:serio_disconnect_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586244400,
      "name": "device_release_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
