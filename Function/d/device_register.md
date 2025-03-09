# Function: <code>device_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584385648,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:1186",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/node.c:register_one_node",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/core.c:__nvdimm_bus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/rtc/class.c:rtc_device_register",
        "drivers/i2c/i2c-core.c:i2c_new_device",
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584385648,
      "name": "device_register",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584720662,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:1186",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/isa.c:isa_register_driver",
        "drivers/base/node.c:register_one_node",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/rtc/class.c:rtc_device_register",
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
        "drivers/i2c/i2c-core.c:i2c_new_device",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584720544,
      "name": "device_register",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584910454,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:1772",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/isa.c:isa_register_driver",
        "drivers/base/node.c:register_one_node",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/rtc/class.c:rtc_device_register",
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
        "drivers/i2c/i2c-core.c:i2c_new_device",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584910336,
      "name": "device_register",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584995734,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:1770",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584995616,
      "name": "device_register",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585417622,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:1905",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio.c:register_virtio_device",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585417504,
      "name": "device_register",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585660353,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:1952",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585660224,
      "name": "device_register",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585786625,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:2031",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585786496,
      "name": "device_register",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586017470,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:2235",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/soundwire/slave.c:sdw_acpi_find_slaves",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586017344,
      "name": "device_register",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586165182,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:2272",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586165056,
      "name": "device_register",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586923518,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:2770",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:tick_init_sysfs",
        "kernel/time/clockevents.c:tick_init_sysfs",
        "drivers/pwm/sysfs.c:pwm_export_child",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv_core.c:pcie_device_init",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_init_cache_dev",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:__vme_register_driver_bus",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "drivers/nvmem/core.c:nvmem_register",
        "drivers/nvmem/core.c:nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586923376,
      "name": "device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587015198,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:3179",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:tick_init_sysfs",
        "kernel/time/clockevents.c:tick_init_sysfs",
        "drivers/pwm/sysfs.c:pwm_export_child",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv_core.c:pcie_device_init",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_init_cache_dev",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:__vme_register_driver_bus",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "drivers/nvmem/core.c:nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587015056,
      "name": "device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586898830,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:3406",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pwm/sysfs.c:pwm_export_child",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:__vme_register_driver_bus",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "drivers/nvmem/core.c:nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586898688,
      "name": "device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587460526,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:3471",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pwm/sysfs.c:pwm_export_child",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/memory.c:init_memory_block",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/wwan/wwan_core.c:wwan_create_dev",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:__vme_register_driver_bus",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "drivers/nvmem/core.c:nvmem_register",
        "drivers/nvmem/core.c:nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587460384,
      "name": "device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588779594,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:3506",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pwm/sysfs.c:pwm_export_child",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/memory.c:add_memory_block",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/wwan/wwan_core.c:wwan_create_port",
        "drivers/net/wwan/wwan_core.c:wwan_create_dev",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:__vme_register_driver_bus",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "drivers/nvmem/core.c:nvmem_register",
        "drivers/nvmem/core.c:nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588779456,
      "name": "device_register",
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
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590273322,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:3705",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "mm/memory-tiers.c:find_create_memory_tier",
        "drivers/pwm/sysfs.c:pwm_export_child",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/memory.c:add_memory_block",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/wwan/wwan_core.c:wwan_create_port",
        "drivers/net/wwan/wwan_core.c:wwan_create_dev",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/staging/vme_user/vme.c:__vme_register_driver_bus",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "drivers/powercap/powercap_sys.c:powercap_register_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590273168,
      "name": "device_register",
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
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590593738,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:3704",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "mm/memory-tiers.c:find_create_memory_tier",
        "drivers/pwm/sysfs.c:pwm_export_child",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/memory.c:add_memory_block",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/wwan/wwan_core.c:wwan_create_port",
        "drivers/net/wwan/wwan_core.c:wwan_create_dev",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/staging/vme_user/vme.c:__vme_register_driver_bus",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "drivers/powercap/powercap_sys.c:powercap_register_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590593584,
      "name": "device_register",
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
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590952649,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:3718",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "mm/memory-tiers.c:find_create_memory_tier",
        "drivers/pwm/sysfs.c:pwm_export_child",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:__dma_async_device_channel_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/memory.c:add_memory_block",
        "drivers/gpu/drm/drm_sysfs.c:drm_class_device_register",
        "drivers/gpu/drm/drm_privacy_screen.c:drm_privacy_screen_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips",
        "drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/staging/vme_user/vme.c:__vme_register_driver_bus",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "drivers/powercap/powercap_sys.c:powercap_register_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590952448,
      "name": "device_register",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498960304,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:2272",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/arm_scmi/bus.c:scmi_device_create",
        "drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498960152,
      "name": "device_register",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231530844,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:2272",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register"
      ],
      "caller_func": [
        "arch/arm/mach-imx/devices/devices.c:mxc_device_init",
        "arch/arm/mach-imx/devices/devices.c:mxc_device_init",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/mtd/mtdcore.c:add_mtd_device",
        "drivers/mtd/mtdcore.c:add_mtd_device",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/arm_scmi/bus.c:scmi_device_create",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "sound/soc/soc-core.c:snd_soc_instantiate_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231530704,
      "name": "device_register",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292105276,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:2272",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register"
      ],
      "caller_func": [
        "arch/powerpc/platforms/pseries/vio.c:vio_bus_init",
        "arch/powerpc/platforms/pseries/vio.c:vio_register_device_node",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292105088,
      "name": "device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276341952,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:2272",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276341808,
      "name": "device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585925550,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:2272",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585925424,
      "name": "device_register",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585774686,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:2272",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/hv/vmbus_drv.c:vmbus_device_register",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/vme/vme.c:vme_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585774560,
      "name": "device_register",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586115198,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:2272",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586115072,
      "name": "device_register",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int device_register(struct device * dev)
```

```json
{
  "name": "device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586223070,
      "name": "device_register",
      "external": true,
      "loc": "drivers/base/core.c:2272",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:__root_device_register"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "kernel/workqueue.c:workqueue_sysfs_register",
        "kernel/time/clocksource.c:init_clocksource_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "kernel/time/clockevents.c:clockevents_init_sysfs",
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/rapidio/rio.c:rio_register_mport",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/video/backlight/backlight.c:backlight_device_register",
        "drivers/pnp/core.c:__pnp_add_device",
        "drivers/pnp/core.c:pnp_register_protocol",
        "drivers/pnp/card.c:pnp_add_card",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/pcpu.c:sync_pcpu",
        "drivers/xen/xen-balloon.c:xen_balloon_init",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:tty_register_device_attr",
        "drivers/base/platform.c:platform_bus_init",
        "drivers/base/cpu.c:register_cpu",
        "drivers/base/isa.c:isa_bus_init",
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/memory.c:init_memory_block",
        "drivers/nvdimm/bus.c:nvdimm_bus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/usb/core/endpoint.c:usb_create_ep_devs",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/hwmon/hwmon.c:__hwmon_device_register",
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register",
        "drivers/eisa/eisa-bus.c:eisa_register_device",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/extcon/extcon.c:extcon_dev_register",
        "drivers/vme/vme.c:vme_register_driver",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586222880,
      "name": "device_register",
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
