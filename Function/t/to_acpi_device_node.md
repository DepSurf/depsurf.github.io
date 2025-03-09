# Function: <code>to_acpi_device_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct acpi_device * to_acpi_device_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "to_acpi_device_node",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583184067,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583189808,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583205001,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583321720,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583339606,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/pci/pcie/portdrv_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583361248,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/pci/hotplug/acpi_pcihp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583375485,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583396848,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_sleep_wake",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:pci_get_hp_params",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583400197,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583549828,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_dev_runtime_resume",
        "drivers/acpi/device_pm.c:acpi_dev_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_runtime_suspend",
        "drivers/acpi/device_pm.c:acpi_dev_suspend_late",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_wake"
      ]
    },
    {
      "addr": 18446744071583558481,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/acpi/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_companion_match"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583559475,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/acpi/glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_platform_notify_remove",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_platform_notify"
      ]
    },
    {
      "addr": 18446744071583592440,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583594057,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_suspend",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr"
      ]
    },
    {
      "addr": 18446744071583605562,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_device_data_of_node",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode"
      ]
    },
    {
      "addr": 18446744071583741317,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/acpi/fan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/fan.c:acpi_fan_probe"
      ]
    },
    {
      "addr": 18446744071583743944,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/acpi/pci_slot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583745149,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/acpi/processor_driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583758667,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/acpi/container.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/container.c:acpi_container_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583808426,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583816163,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583818526,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583898058,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584259310,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584420992,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/base/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_dma_supported",
        "drivers/base/property.c:device_get_dma_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584655590,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585009143,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_dissociate",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585015240,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/ata/libata-zpodd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585033375,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_add_device",
        "drivers/spi/spi.c:spi_register_master"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585185759,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585269775,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585539406,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585631317,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_device_probe",
        "drivers/i2c/i2c-core.c:i2c_new_device",
        "drivers/i2c/i2c-core.c:acpi_i2c_add_device",
        "drivers/i2c/i2c-core.c:i2c_register_adapter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585967352,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_add_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583549828,
      "name": "to_acpi_device_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071583559475,
      "name": "to_acpi_device_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071583594057,
      "name": "to_acpi_device_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071583605562,
      "name": "to_acpi_device_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071583741317,
      "name": "to_acpi_device_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct acpi_device * to_acpi_device_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "to_acpi_device_node",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583483453,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583505155,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583517791,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583551130,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583632809,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583651664,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pci/pcie/portdrv_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583675743,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pci/hotplug/acpi_pcihp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583694233,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583712087,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_sleep_wake",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pci_get_hp_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583714693,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583871857,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume_early",
        "drivers/acpi/device_pm.c:acpi_dev_suspend_late",
        "drivers/acpi/device_pm.c:acpi_dev_runtime_resume",
        "drivers/acpi/device_pm.c:acpi_dev_runtime_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_wake",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state"
      ]
    },
    {
      "addr": 18446744071583880136,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_companion_match"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583880781,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/glue.c:acpi_platform_notify_remove",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one"
      ]
    },
    {
      "addr": 18446744071583915047,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583917057,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read"
      ]
    },
    {
      "addr": 18446744071583928831,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ]
    },
    {
      "addr": 18446744071584066500,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/fan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/fan.c:acpi_fan_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584068346,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/pci_slot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584069569,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/processor_driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584084582,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/container.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/container.c:acpi_container_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584134691,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584145374,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584229050,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584600358,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584629547,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:get_irq_domain",
        "drivers/iommu/amd_iommu.c:get_irq_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_dm_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_dm_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:check_device",
        "drivers/iommu/amd_iommu.c:check_device",
        "drivers/iommu/amd_iommu.c:get_alias",
        "drivers/iommu/amd_iommu.c:get_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584756784,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/base/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585004191,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585380957,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_dissociate",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_dev_acpi_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585383080,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/ata/libata-zpodd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585416976,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_acpi_device_match",
        "drivers/spi/spi.c:spi_acpi_master_match",
        "drivers/spi/spi.c:spi_register_master",
        "drivers/spi/spi.c:spi_unregister_device",
        "drivers/spi/spi.c:spi_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585577871,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585665549,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585933211,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586045059,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
        "drivers/i2c/i2c-core.c:i2c_unregister_device",
        "drivers/i2c/i2c-core.c:i2c_new_device",
        "drivers/i2c/i2c-core.c:i2c_device_probe",
        "drivers/i2c/i2c-core.c:acpi_i2c_match_device",
        "drivers/i2c/i2c-core.c:acpi_i2c_match_adapter",
        "drivers/i2c/i2c-core.c:acpi_i2c_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586372776,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_add_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871857,
      "name": "to_acpi_device_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583880781,
      "name": "to_acpi_device_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071583917057,
      "name": "to_acpi_device_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583928831,
      "name": "to_acpi_device_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct acpi_device * to_acpi_device_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "to_acpi_device_node",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583616365,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583623533,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583645082,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583658719,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583687682,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595654803,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583770137,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583789328,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pci/pcie/portdrv_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583813951,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pci/hotplug/acpi_pcihp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583832345,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583850855,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_sleep_wake",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pciehp_is_native",
        "drivers/pci/pci-acpi.c:pci_get_hp_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583853573,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584010909,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume_early",
        "drivers/acpi/device_pm.c:acpi_dev_suspend_late",
        "drivers/acpi/device_pm.c:acpi_dev_runtime_resume",
        "drivers/acpi/device_pm.c:acpi_dev_runtime_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_wake",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state"
      ]
    },
    {
      "addr": 18446744071584019190,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_companion_match"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584019854,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/glue.c:acpi_platform_notify_remove",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one"
      ]
    },
    {
      "addr": 18446744071584055935,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584057953,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read"
      ]
    },
    {
      "addr": 18446744071584070026,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ]
    },
    {
      "addr": 18446744071584208985,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/fan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/fan.c:acpi_fan_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584210831,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/pci_slot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584212101,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/processor_driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584227168,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/acpi/container.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/container.c:acpi_container_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584282691,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584325950,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584410522,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584781798,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584814683,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:get_irq_domain",
        "drivers/iommu/amd_iommu.c:get_irq_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:check_device",
        "drivers/iommu/amd_iommu.c:check_device",
        "drivers/iommu/amd_iommu.c:get_alias",
        "drivers/iommu/amd_iommu.c:get_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/base/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584947008,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/base/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585187647,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585581789,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_dissociate",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_dev_acpi_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585583912,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/ata/libata-zpodd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585617888,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_acpi_device_match",
        "drivers/spi/spi.c:spi_acpi_master_match",
        "drivers/spi/spi.c:spi_register_master",
        "drivers/spi/spi.c:spi_unregister_device",
        "drivers/spi/spi.c:spi_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585765519,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585853245,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586121563,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586242552,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
        "drivers/i2c/i2c-core.c:i2c_unregister_device",
        "drivers/i2c/i2c-core.c:i2c_new_device",
        "drivers/i2c/i2c-core.c:i2c_device_probe",
        "drivers/i2c/i2c-core.c:i2c_acpi_match_device",
        "drivers/i2c/i2c-core.c:i2c_acpi_match_adapter",
        "drivers/i2c/i2c-core.c:i2c_acpi_find_bus_speed",
        "drivers/i2c/i2c-core.c:i2c_acpi_get_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586581608,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:406",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_add_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584010909,
      "name": "to_acpi_device_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584019854,
      "name": "to_acpi_device_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071584057953,
      "name": "to_acpi_device_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584070026,
      "name": "to_acpi_device_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "to_acpi_device_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583655533,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583658238,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583685881,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583698815,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596576602,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583811849,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583832657,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/pci/pcie/portdrv_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583856912,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/pci/hotplug/acpi_pcihp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583874808,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583891763,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pciehp_is_native",
        "drivers/pci/pci-acpi.c:pci_get_hp_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583894389,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584065692,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume_early",
        "drivers/acpi/device_pm.c:acpi_dev_suspend_late",
        "drivers/acpi/device_pm.c:acpi_dev_runtime_resume",
        "drivers/acpi/device_pm.c:acpi_dev_runtime_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584072371,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/acpi/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_companion_match"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584074035,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/acpi/glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/glue.c:acpi_platform_notify_remove",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584116700,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584118716,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584134540,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_device_is_available",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584278703,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/acpi/fan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/fan.c:acpi_fan_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584280563,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/acpi/pci_slot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584282163,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/acpi/processor_driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584299603,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/acpi/container.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/container.c:acpi_container_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584360691,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/pnp/pnpacpi/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584405912,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/dma/acpi-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584493839,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584870189,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584907399,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:get_irq_domain",
        "drivers/iommu/amd_iommu.c:get_irq_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:get_alias",
        "drivers/iommu/amd_iommu.c:get_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/base/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585032448,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/base/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported",
        "drivers/base/property.c:device_get_next_child_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585096562,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/base/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dma-mapping.c:dma_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585269789,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585665258,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_dissociate",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_dev_acpi_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585667432,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/ata/libata-zpodd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585701664,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_acpi_device_match",
        "drivers/spi/spi.c:spi_acpi_controller_match",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_unregister_device",
        "drivers/spi/spi.c:spi_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585852365,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585939519,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586209766,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586312240,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_unregister_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586335965,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_adapter",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586346501,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586348444,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/i2c/busses/i2c-designware-baytrail.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586706600,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:409",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_add_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "to_acpi_device_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/linux/acpi.h:699",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/linux/acpi.h:699",
      "file": "drivers/base/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "to_acpi_device_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/linux/acpi.h:699",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/linux/acpi.h:699",
      "file": "drivers/base/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "to_acpi_device_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/linux/acpi.h:699",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "to_acpi_device_node",
      "external": false,
      "loc": "include/linux/acpi.h:699",
      "file": "drivers/base/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct acpi_device * to_acpi_device_node(struct fwnode_handle * fwnode)
```
</details>
</li>
</ul>
