# Function: <code>class_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584402624,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:274",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/usb/core/file.c:release_usb_class",
        "drivers/rtc/class.c:rtc_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/power/power_supply_core.c:power_supply_class_exit",
        "drivers/watchdog/watchdog_core.c:watchdog_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/devfreq/devfreq.c:devfreq_exit",
        "drivers/devfreq/devfreq-event.c:devfreq_event_exit",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584402624,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584737968,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:274",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:release_usb_class",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/power/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584737968,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584927856,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:289",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:release_usb_class",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584927856,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585012560,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:256",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_exit",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585012560,
      "name": "class_destroy",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585434816,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:256",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_exit",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:release_usb_class",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585434816,
      "name": "class_destroy",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585677984,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:254",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_exit",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:release_usb_class",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585677984,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585808240,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:254",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_exit",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:release_usb_class",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585808240,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586041504,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:260",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "block/bsg.c:bsg_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:release_usb_class",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586041504,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586189136,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:260",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "block/bsg.c:bsg_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/file.c:release_usb_class",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586189136,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586950848,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:261",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "block/bsg.c:bsg_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586950848,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587035840,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:261",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "block/bsg.c:bsg_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/usb/roles/class.c:usb_roles_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587035840,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586919632,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:261",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "block/bsg.c:bsg_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_exit",
        "drivers/net/wwan/wwan_core.c:wwan_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/usb/roles/class.c:usb_roles_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586919632,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587482032,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:261",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "block/bsg.c:bsg_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_exit",
        "drivers/net/wwan/wwan_core.c:wwan_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/usb/roles/class.c:usb_roles_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587482032,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588803680,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:261",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "block/bsg.c:bsg_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtio_console_fini",
        "drivers/char/virtio_console.c:virtio_console_init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_exit",
        "drivers/net/wwan/wwan_core.c:wwan_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/usb/roles/class.c:usb_roles_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588803680,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590300864,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:266",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "block/bsg.c:bsg_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtio_console_fini",
        "drivers/char/virtio_console.c:virtio_console_init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_exit",
        "drivers/net/wwan/wwan_core.c:wwan_init",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/usb/roles/class.c:usb_roles_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590300864,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void class_destroy(const struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590622112,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:289",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "drivers/phy/phy-core.c:phy_core_exit",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_exit",
        "drivers/net/wwan/wwan_core.c:wwan_init",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590622112,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void class_destroy(const struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590981360,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:288",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_core_exit",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_destroy",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590981360,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498988856,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:260",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/usb/roles/class.c:usb_roles_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498988856,
      "name": "class_destroy",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231557120,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:260",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/usb/gadget/udc/core.c:usb_udc_exit",
        "drivers/usb/roles/class.c:usb_roles_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/extcon/extcon.c:extcon_class_exit",
        "sound/sound_core.c:cleanup_soundcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231557120,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292141664,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:260",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292141664,
      "name": "class_destroy",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276363896,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:260",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg.c:bsg_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_deregister_dev",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276363896,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585949504,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:260",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "block/bsg.c:bsg_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/nvme/host/core.c:nvme_core_exit",
        "drivers/nvme/host/core.c:nvme_core_exit",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:release_usb_class",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585949504,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585798560,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:260",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "block/bsg.c:bsg_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/nvme/host/core.c:nvme_core_exit",
        "drivers/nvme/host/core.c:nvme_core_exit",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/file.c:release_usb_class",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/devfreq/devfreq.c:devfreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585798560,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586139152,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:260",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "block/bsg.c:bsg_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/file.c:release_usb_class",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586139152,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void class_destroy(struct class * cls)
```

```json
{
  "name": "class_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586247840,
      "name": "class_destroy",
      "external": true,
      "loc": "drivers/base/class.c:260",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release",
        "block/bsg.c:bsg_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_exit",
        "drivers/video/backlight/backlight.c:backlight_class_exit",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:fini",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_exit",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_exit",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_cleanup",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/file.c:release_usb_class",
        "drivers/i2c/i2c-dev.c:i2c_dev_exit",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/pps/pps.c:pps_exit",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/ptp/ptp_clock.c:ptp_exit",
        "drivers/power/supply/power_supply_core.c:power_supply_class_exit",
        "drivers/leds/led-class.c:leds_exit",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/extcon/extcon.c:extcon_class_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586247840,
      "name": "class_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct class * cls</code> ➡️ <code>const struct class * cls</code>
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
