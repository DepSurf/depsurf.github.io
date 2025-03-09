# Function: <code>bus_find_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct device * bus_find_device(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584389792,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:335",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:store_drivers_probe",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584389792,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584724720,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:334",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/base/bus.c:store_drivers_probe",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584724720,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584914512,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:334",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/base/bus.c:store_drivers_probe",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584914512,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584999824,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:334",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/acpi/utils.c:acpi_dev_present",
        "drivers/base/bus.c:store_drivers_probe",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path",
        "drivers/nvmem/core.c:devm_nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584999824,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585421760,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:334",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/acpi/utils.c:acpi_dev_present",
        "drivers/base/bus.c:store_drivers_probe",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path",
        "drivers/nvmem/core.c:devm_nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585421760,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585664544,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:332",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/acpi/utils.c:acpi_dev_get_first_match_name",
        "drivers/acpi/utils.c:acpi_dev_present",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/base/bus.c:store_drivers_probe",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585664544,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, void * data, int (*)(struct device *, void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585794224,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:335",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/acpi/utils.c:acpi_dev_get_first_match_name",
        "drivers/acpi/utils.c:acpi_dev_present",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_find_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_find_device",
        "drivers/base/bus.c:store_drivers_probe",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585794224,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586027504,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:325",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/acpi/utils.c:acpi_dev_get_first_match_dev",
        "drivers/acpi/utils.c:acpi_dev_present",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_find_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_find_device",
        "drivers/base/bus.c:drivers_probe_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586027504,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586174960,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:325",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/acpi/utils.c:acpi_dev_get_first_match_dev",
        "drivers/acpi/utils.c:acpi_dev_present",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_find_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_find_device",
        "drivers/base/bus.c:drivers_probe_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/platform.c:platform_find_device_by_driver",
        "drivers/mfd/mfd-core.c:mfd_clone_cell",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/net/phy/phy_device.c:phy_connect",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586174960,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586934880,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:326",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/acpi/utils.c:acpi_dev_get_first_match_dev",
        "drivers/acpi/utils.c:acpi_dev_present",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer",
        "drivers/base/bus.c:drivers_probe_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/platform.c:platform_find_device_by_driver",
        "drivers/base/devcon.c:device_connection_fwnode_match",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/net/phy/phy_device.c:phy_connect",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path",
        "drivers/nvmem/core.c:__nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586934880,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587020176,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:326",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/acpi/utils.c:acpi_dev_get_first_match_dev",
        "drivers/acpi/utils.c:acpi_dev_present",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer",
        "drivers/base/bus.c:drivers_probe_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/platform.c:platform_find_device_by_driver",
        "drivers/base/auxiliary.c:auxiliary_find_device",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/net/phy/phy_device.c:phy_connect",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path",
        "drivers/nvmem/core.c:__nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587020176,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586903808,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:326",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_class",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/acpi/utils.c:acpi_dev_get_next_match_dev",
        "drivers/acpi/utils.c:acpi_dev_get_next_match_dev",
        "drivers/acpi/utils.c:acpi_dev_present",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/base/bus.c:drivers_probe_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/platform.c:platform_find_device_by_driver",
        "drivers/base/auxiliary.c:auxiliary_find_device",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/net/phy/phy_device.c:phy_connect",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/nvmem/core.c:__nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586903808,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587465568,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:322",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_class",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/acpi/utils.c:acpi_dev_get_next_match_dev",
        "drivers/acpi/utils.c:acpi_dev_get_next_match_dev",
        "drivers/acpi/utils.c:acpi_dev_present",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/base/bus.c:drivers_probe_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/platform.c:platform_find_device_by_driver",
        "drivers/base/auxiliary.c:auxiliary_find_device",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/net/phy/phy_device.c:fwnode_phy_find_device",
        "drivers/net/phy/phy_device.c:phy_connect",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/nvmem/core.c:__nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587465568,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588785664,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:322",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_class",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/acpi/utils.c:acpi_dev_get_next_match_dev",
        "drivers/acpi/utils.c:acpi_dev_get_next_match_dev",
        "drivers/acpi/utils.c:acpi_dev_present",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/base/bus.c:drivers_probe_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/platform.c:platform_find_device_by_driver",
        "drivers/base/auxiliary.c:auxiliary_find_device",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/net/phy/phy_device.c:fwnode_phy_find_device",
        "drivers/net/phy/phy_device.c:phy_connect",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/nvmem/core.c:__nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588785664,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590280592,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:322",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_class",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/p2pdma.c:pci_p2pdma_enable_store",
        "drivers/acpi/utils.c:acpi_dev_get_next_match_dev",
        "drivers/acpi/utils.c:acpi_dev_present",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/base/bus.c:drivers_probe_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/platform.c:platform_find_device_by_driver",
        "drivers/base/auxiliary.c:auxiliary_find_device",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/net/phy/phy_device.c:fwnode_phy_find_device",
        "drivers/net/phy/phy_device.c:phy_connect",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/nvmem/core.c:__nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590280592,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
struct device * bus_find_device(const struct bus_type * bus, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590602000,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:390",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_class",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/p2pdma.c:pci_p2pdma_enable_store",
        "drivers/acpi/utils.c:acpi_dev_get_next_match_dev",
        "drivers/acpi/utils.c:acpi_dev_present",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/base/bus.c:drivers_probe_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/platform.c:platform_find_device_by_driver",
        "drivers/base/auxiliary.c:auxiliary_find_device",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/net/phy/phy_device.c:fwnode_phy_find_device",
        "drivers/net/phy/phy_device.c:phy_connect",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-base.c:i2c_find_adapter_by_fwnode",
        "drivers/i2c/i2c-core-base.c:i2c_find_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_allocate_context",
        "drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog",
        "drivers/nvmem/core.c:__nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590602000,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct device * bus_find_device(const struct bus_type * bus, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590960944,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:390",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_dev_present",
        "drivers/pci/search.c:pci_get_base_class",
        "drivers/pci/search.c:pci_get_class",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/p2pdma.c:pci_p2pdma_enable_store",
        "drivers/acpi/utils.c:acpi_dev_get_next_match_dev",
        "drivers/acpi/utils.c:acpi_dev_present",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/base/bus.c:drivers_probe_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/platform.c:platform_find_device_by_driver",
        "drivers/base/auxiliary.c:auxiliary_find_device",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/net/phy/phy_device.c:fwnode_phy_find_device",
        "drivers/net/phy/phy_device.c:phy_connect",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-base.c:i2c_find_adapter_by_fwnode",
        "drivers/i2c/i2c-core-base.c:i2c_find_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_allocate_context",
        "drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog",
        "drivers/nvmem/core.c:__nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590960944,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498971744,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:325",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/acpi/utils.c:acpi_dev_get_first_match_dev",
        "drivers/acpi/utils.c:acpi_dev_present",
        "drivers/base/bus.c:drivers_probe_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/platform.c:platform_find_device_by_driver",
        "drivers/mfd/mfd-core.c:mfd_clone_cell",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/net/phy/phy_device.c:phy_connect",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle",
        "drivers/i2c/i2c-core-of.c:of_find_i2c_adapter_by_node",
        "drivers/i2c/i2c-core-of.c:of_find_i2c_device_by_node",
        "drivers/of/of_mdio.c:of_phy_find_device",
        "drivers/nvmem/core.c:__nvmem_device_get",
        "drivers/nvmem/core.c:__nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498971744,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231541352,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:325",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/base/bus.c:drivers_probe_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/platform.c:platform_find_device_by_driver",
        "drivers/mfd/mfd-core.c:mfd_clone_cell",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/net/phy/phy_device.c:phy_connect",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-of.c:of_find_i2c_adapter_by_node",
        "drivers/i2c/i2c-core-of.c:of_find_i2c_device_by_node",
        "drivers/of/of_mdio.c:of_phy_find_device",
        "drivers/nvmem/core.c:__nvmem_device_get",
        "drivers/nvmem/core.c:__nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231541352,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292119120,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:325",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/vio.c:vio_find_node",
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/base/bus.c:drivers_probe_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/platform.c:platform_find_device_by_driver",
        "drivers/mfd/mfd-core.c:mfd_clone_cell",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/net/phy/phy_device.c:phy_connect",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-of.c:of_find_i2c_adapter_by_node",
        "drivers/i2c/i2c-core-of.c:of_find_i2c_device_by_node",
        "drivers/of/of_mdio.c:of_phy_find_device",
        "drivers/nvmem/core.c:__nvmem_device_get",
        "drivers/nvmem/core.c:__nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292119120,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276350648,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:325",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/base/bus.c:drivers_probe_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/platform.c:platform_find_device_by_driver",
        "drivers/mfd/mfd-core.c:mfd_clone_cell",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/net/phy/phy_device.c:phy_connect",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-of.c:of_find_i2c_adapter_by_node",
        "drivers/i2c/i2c-core-of.c:of_find_i2c_device_by_node",
        "drivers/of/of_mdio.c:of_phy_find_device",
        "drivers/nvmem/core.c:__nvmem_device_get",
        "drivers/nvmem/core.c:__nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276350648,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585935328,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:325",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/acpi/utils.c:acpi_dev_get_first_match_dev",
        "drivers/acpi/utils.c:acpi_dev_present",
        "drivers/base/bus.c:drivers_probe_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/platform.c:platform_find_device_by_driver",
        "drivers/mfd/mfd-core.c:mfd_clone_cell",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/net/phy/phy_device.c:phy_connect",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585935328,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585784464,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:325",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/acpi/utils.c:acpi_dev_get_first_match_dev",
        "drivers/acpi/utils.c:acpi_dev_present",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_find_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_find_device",
        "drivers/base/bus.c:drivers_probe_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/platform.c:platform_find_device_by_driver",
        "drivers/mfd/mfd-core.c:mfd_clone_cell",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/net/phy/phy_device.c:phy_connect",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585784464,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586124976,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:325",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/acpi/utils.c:acpi_dev_get_first_match_dev",
        "drivers/acpi/utils.c:acpi_dev_present",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_find_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_find_device",
        "drivers/base/bus.c:drivers_probe_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/platform.c:platform_find_device_by_driver",
        "drivers/mfd/mfd-core.c:mfd_clone_cell",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/net/phy/phy_device.c:phy_connect",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586124976,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
struct device * bus_find_device(struct bus_type * bus, struct device * start, const void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "bus_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586233584,
      "name": "bus_find_device",
      "external": true,
      "loc": "drivers/base/bus.c:325",
      "file": "drivers/base/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:no_pci_devices",
        "drivers/pci/search.c:pci_get_dev_by_id",
        "drivers/acpi/utils.c:acpi_dev_get_first_match_dev",
        "drivers/acpi/utils.c:acpi_dev_present",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_find_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_find_device",
        "drivers/base/bus.c:drivers_probe_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:bind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/bus.c:unbind_store",
        "drivers/base/platform.c:platform_find_device_by_driver",
        "drivers/mfd/mfd-core.c:mfd_clone_cell",
        "drivers/scsi/scsi_proc.c:scsi_seq_next",
        "drivers/scsi/scsi_proc.c:scsi_seq_start",
        "drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node",
        "drivers/net/phy/phy_device.c:phy_connect",
        "drivers/usb/core/usb.c:usb_find_interface",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle",
        "drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586233584,
      "name": "bus_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void * data</code> ➡️ <code>const void * data</code>
</li>
<li>
<b>Param type changed. </b>
<code>int (*)(struct device *, void *) match</code> ➡️ <code>int (*)(struct device *, const void *) match</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bus_type * bus</code> ➡️ <code>const struct bus_type * bus</code>
</li>
</ul>
</details>
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
