# Function: <code>__class_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584404672,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:239",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/power/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584404672,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584740016,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:239",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/power/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584740016,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584929968,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:254",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584929968,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585014544,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:221",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585014544,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585436800,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:221",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585436800,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585679920,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:219",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_class_init",
        "mm/hmm.c:hmm_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/rtc/class.c:rtc_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585679920,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585810144,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:219",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "mm/backing-dev.c:bdi_class_init",
        "mm/hmm.c:hmm_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/rtc/class.c:rtc_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585810144,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586043376,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:225",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/rtc/class.c:rtc_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043376,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586191008,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:225",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/rtc/class.c:rtc_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586191008,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586951760,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:226",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/dma-buf/dma-heap.c:dma_heap_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/file.c:init_usb_class",
        "drivers/rtc/class.c:rtc_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init",
        "drivers/extcon/extcon.c:extcon_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586951760,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587036736,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:226",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/dma-buf/dma-heap.c:dma_heap_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/file.c:init_usb_class",
        "drivers/usb/roles/class.c:usb_roles_init",
        "drivers/rtc/class.c:rtc_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init",
        "drivers/extcon/extcon.c:extcon_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036736,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586920528,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:226",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/dma-buf/dma-heap.c:dma_heap_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/roles/class.c:usb_roles_init",
        "drivers/rtc/class.c:rtc_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init",
        "drivers/extcon/extcon.c:extcon_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586920528,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587482928,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:226",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/dma-buf/dma-heap.c:dma_heap_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/roles/class.c:usb_roles_init",
        "drivers/rtc/class.c:rtc_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init",
        "drivers/extcon/extcon.c:extcon_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587482928,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588804784,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:226",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtio_console_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dma-buf/dma-heap.c:dma_heap_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/usb/roles/class.c:usb_roles_init",
        "drivers/rtc/class.c:rtc_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/extcon/extcon.c:create_extcon_class"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588804784,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590302112,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:231",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:virtio_console_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dma-buf/dma-heap.c:dma_heap_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_init",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/usb/roles/class.c:usb_roles_init",
        "drivers/rtc/class.c:rtc_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init",
        "drivers/extcon/extcon.c:extcon_class_init",
        "drivers/extcon/extcon.c:extcon_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590302112,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498988552,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:225",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/bus/vexpress-config.c:vexpress_config_bridge_register",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/roles/class.c:usb_roles_init",
        "drivers/rtc/class.c:rtc_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498988552,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231556848,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:225",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/bus/vexpress-config.c:vexpress_config_bridge_register",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/usb/gadget/udc/core.c:usb_udc_init",
        "drivers/usb/roles/class.c:usb_roles_init",
        "drivers/rtc/class.c:rtc_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init",
        "sound/sound_core.c:init_soundcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231556848,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292144496,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:225",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/rtc/class.c:rtc_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292144496,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276365606,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:225",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/rtc/class.c:rtc_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276365606,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585951376,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:225",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/rtc/class.c:rtc_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585951376,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585800432,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:225",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/nvme/host/core.c:nvme_core_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/rtc/class.c:rtc_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585800432,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586141024,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:225",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/rtc/class.c:rtc_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586141024,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586249712,
      "name": "__class_create",
      "external": true,
      "loc": "drivers/base/class.c:225",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "mm/backing-dev.c:bdi_class_init",
        "block/bsg.c:bsg_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/tty_io.c:tty_class_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/mem.c:chr_dev_init",
        "drivers/char/misc.c:misc_init",
        "drivers/char/virtio_console.c:init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/dax/bus.c:dax_bus_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/vfio/vfio.c:vfio_init",
        "drivers/rtc/class.c:rtc_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586249712,
      "name": "__class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
struct class * __class_create(struct module * owner, const char * name, struct lock_class_key * key)
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
