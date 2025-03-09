# Function: <code>add_uevent_var</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582959872,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:386",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias",
        "drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/firmware_class.c:firmware_uevent",
        "drivers/base/firmware_class.c:firmware_uevent",
        "drivers/base/firmware_class.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/power/power_supply_sysfs.c:power_supply_uevent",
        "drivers/power/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582959872,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583247296,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:386",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_uevent",
        "block/partition-generic.c:part_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias",
        "drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/firmware_class.c:firmware_uevent",
        "drivers/base/firmware_class.c:firmware_uevent",
        "drivers/base/firmware_class.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/power_supply_sysfs.c:power_supply_uevent",
        "drivers/power/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583247296,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583362608,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:386",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_uevent",
        "block/partition-generic.c:part_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias",
        "drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/firmware_class.c:firmware_uevent",
        "drivers/base/firmware_class.c:firmware_uevent",
        "drivers/base/firmware_class.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583362608,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588212848,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:527",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_uevent",
        "block/partition-generic.c:part_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/firmware_class.c:firmware_uevent",
        "drivers/base/firmware_class.c:firmware_uevent",
        "drivers/base/firmware_class.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588212848,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588762448,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:578",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_uevent",
        "block/partition-generic.c:part_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/firmware_class.c:firmware_uevent",
        "drivers/base/firmware_class.c:firmware_uevent",
        "drivers/base/firmware_class.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588762448,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589140608,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:648",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_uevent",
        "block/partition-generic.c:part_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589140608,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589375648,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:650",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_uevent",
        "block/partition-generic.c:part_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/eisa/eisa-bus.c:eisa_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589375648,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589832832,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:653",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_uevent",
        "block/partition-generic.c:part_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/dax/bus.c:dax_bus_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/eisa/eisa-bus.c:eisa_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent",
        "drivers/soundwire/bus_type.c:sdw_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589832832,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590058976,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:653",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_uevent",
        "block/partition-generic.c:part_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/dax/bus.c:dax_bus_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/eisa/eisa-bus.c:eisa_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590058976,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585054720,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:653",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:part_uevent",
        "block/partitions/core.c:part_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_action_args",
        "lib/kobject_uevent.c:kobject_action_args",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/dax/bus.c:dax_bus_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_build_path_uevent",
        "drivers/md/dm-uevent.c:dm_build_path_uevent",
        "drivers/md/dm-uevent.c:dm_build_path_uevent",
        "drivers/md/dm-uevent.c:dm_build_path_uevent",
        "drivers/md/dm-uevent.c:dm_build_path_uevent",
        "drivers/eisa/eisa-bus.c:eisa_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585054720,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585204192,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:653",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:part_uevent",
        "block/partitions/core.c:part_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_action_args",
        "lib/kobject_uevent.c:kobject_action_args",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/auxiliary.c:auxiliary_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/dax/bus.c:dax_bus_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/roles/class.c:usb_role_switch_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_build_path_uevent",
        "drivers/md/dm-uevent.c:dm_build_path_uevent",
        "drivers/md/dm-uevent.c:dm_build_path_uevent",
        "drivers/md/dm-uevent.c:dm_build_path_uevent",
        "drivers/md/dm-uevent.c:dm_build_path_uevent",
        "drivers/eisa/eisa-bus.c:eisa_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585204192,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585087136,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:654",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/core.c:part_uevent",
        "block/partitions/core.c:part_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_action_args",
        "lib/kobject_uevent.c:kobject_action_args",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/auxiliary.c:auxiliary_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/dax/bus.c:dax_bus_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/roles/class.c:usb_role_switch_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/eisa/eisa-bus.c:eisa_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585087136,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585534352,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:654",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:block_uevent",
        "block/partitions/core.c:part_uevent",
        "block/partitions/core.c:part_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_action_args",
        "lib/kobject_uevent.c:kobject_action_args",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/auxiliary.c:auxiliary_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/dax/bus.c:dax_bus_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/phy/phy.c:usb_phy_uevent",
        "drivers/usb/phy/phy.c:usb_phy_uevent",
        "drivers/usb/roles/class.c:usb_role_switch_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/eisa/eisa-bus.c:eisa_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585534352,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586688768,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:654",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:block_uevent",
        "block/partitions/core.c:part_uevent",
        "block/partitions/core.c:part_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_action_args",
        "lib/kobject_uevent.c:kobject_action_args",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/auxiliary.c:auxiliary_uevent",
        "drivers/base/firmware_loader/sysfs.c:firmware_uevent",
        "drivers/base/firmware_loader/sysfs.c:firmware_uevent",
        "drivers/base/firmware_loader/sysfs.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/dax/bus.c:dax_bus_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/phy/phy.c:usb_phy_uevent",
        "drivers/usb/phy/phy.c:usb_phy_uevent",
        "drivers/usb/roles/class.c:usb_role_switch_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/eisa/eisa-bus.c:eisa_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586688768,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595769264,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:654",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:block_uevent",
        "block/partitions/core.c:part_uevent",
        "block/partitions/core.c:part_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/auxiliary.c:auxiliary_uevent",
        "drivers/base/firmware_loader/sysfs.c:firmware_uevent",
        "drivers/base/firmware_loader/sysfs.c:firmware_uevent",
        "drivers/base/firmware_loader/sysfs.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/dax/bus.c:dax_bus_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/phy/phy.c:usb_phy_uevent",
        "drivers/usb/phy/phy.c:usb_phy_uevent",
        "drivers/usb/roles/class.c:usb_role_switch_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/eisa/eisa-bus.c:eisa_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_action_args",
        "lib/kobject_uevent.c:kobject_action_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595769264,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596293808,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:654",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:block_uevent",
        "block/partitions/core.c:part_uevent",
        "block/partitions/core.c:part_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/auxiliary.c:auxiliary_uevent",
        "drivers/base/firmware_loader/sysfs.c:firmware_uevent",
        "drivers/base/firmware_loader/sysfs.c:firmware_uevent",
        "drivers/base/firmware_loader/sysfs.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/dax/bus.c:dax_bus_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/phy/phy.c:usb_phy_uevent",
        "drivers/usb/phy/phy.c:usb_phy_uevent",
        "drivers/usb/roles/class.c:usb_role_switch_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/eisa/eisa-bus.c:eisa_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_action_args",
        "lib/kobject_uevent.c:kobject_action_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596293808,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597178752,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:654",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:block_uevent",
        "block/partitions/core.c:part_uevent",
        "block/partitions/core.c:part_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/auxiliary.c:auxiliary_uevent",
        "drivers/base/firmware_loader/sysfs.c:firmware_uevent",
        "drivers/base/firmware_loader/sysfs.c:firmware_uevent",
        "drivers/base/firmware_loader/sysfs.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/dax/bus.c:dax_bus_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/phy/phy.c:usb_phy_uevent",
        "drivers/usb/phy/phy.c:usb_phy_uevent",
        "drivers/usb/roles/class.c:usb_role_switch_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_path_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/eisa/eisa-bus.c:eisa_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/bus.c:mmc_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_action_args",
        "lib/kobject_uevent.c:kobject_action_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597178752,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503836480,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:653",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_uevent",
        "block/partition-generic.c:part_uevent",
        "drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/dax/bus.c:dax_bus_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/roles/class.c:usb_role_switch_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent",
        "drivers/of/device.c:of_device_uevent_modalias",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503836480,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236455148,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:653",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_uevent",
        "block/partition-generic.c:part_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/dax/bus.c:dax_bus_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/gadget/udc/core.c:usb_udc_uevent",
        "drivers/usb/gadget/udc/core.c:usb_udc_uevent",
        "drivers/usb/roles/class.c:usb_role_switch_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent",
        "drivers/of/device.c:of_device_uevent_modalias",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236455148,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297685696,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:653",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/vio.c:vio_hotplug",
        "block/partition-generic.c:part_uevent",
        "block/partition-generic.c:part_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/dax/bus.c:dax_bus_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/of/device.c:of_device_uevent_modalias",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297685696,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279727942,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:653",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_uevent",
        "block/partition-generic.c:part_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/dax/bus.c:dax_bus_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/of/device.c:of_device_uevent_modalias",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "drivers/of/device.c:of_device_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279727942,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589661232,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:653",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_uevent",
        "block/partition-generic.c:part_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/dax/bus.c:dax_bus_uevent",
        "drivers/nvme/host/core.c:nvme_class_uevent",
        "drivers/nvme/host/core.c:nvme_class_uevent",
        "drivers/nvme/host/core.c:nvme_class_uevent",
        "drivers/nvme/host/core.c:nvme_class_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/eisa/eisa-bus.c:eisa_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589661232,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589387056,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:653",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_uevent",
        "block/partition-generic.c:part_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/dax/bus.c:dax_bus_uevent",
        "drivers/nvme/host/core.c:nvme_class_uevent",
        "drivers/nvme/host/core.c:nvme_class_uevent",
        "drivers/nvme/host/core.c:nvme_class_uevent",
        "drivers/nvme/host/core.c:nvme_class_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/eisa/eisa-bus.c:eisa_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent",
        "drivers/hv/vmbus_drv.c:vmbus_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589387056,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590104608,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:653",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_uevent",
        "block/partition-generic.c:part_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/dax/bus.c:dax_bus_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/eisa/eisa-bus.c:eisa_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590104608,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int add_uevent_var(struct kobj_uevent_env * env, const char * format, void (anon))
```

```json
{
  "name": "add_uevent_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590154912,
      "name": "add_uevent_var",
      "external": true,
      "loc": "lib/kobject_uevent.c:653",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:part_uevent",
        "block/partition-generic.c:part_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/pci/pci-driver.c:pci_uevent",
        "drivers/rapidio/rio-driver.c:rio_uevent",
        "drivers/virtio/virtio.c:virtio_uevent",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/core.c:dev_uevent",
        "drivers/base/cpu.c:cpu_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/base/firmware_loader/fallback.c:firmware_uevent",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/dax/bus.c:dax_bus_uevent",
        "drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent",
        "drivers/spi/spi.c:spi_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/usb.c:usb_dev_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/message.c:usb_if_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/usb/core/driver.c:usb_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/serio/serio.c:serio_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_dev_uevent",
        "drivers/input/input.c:input_add_uevent_bm_var",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/md/dm-uevent.c:dm_send_uevents",
        "drivers/eisa/eisa-bus.c:eisa_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_uevent",
        "drivers/firmware/dmi-id.c:dmi_dev_uevent",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590154912,
      "name": "add_uevent_var",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
