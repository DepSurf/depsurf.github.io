# Function: <code>is_acpi_device_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583184067,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583189808,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
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
      "addr": 18446744071583241690,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583321720,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583339606,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/pci/pcie/portdrv_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583361248,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583549831,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:to_acpi_device_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583558481,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/acpi/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_companion_match"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583559478,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/acpi/glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/glue.c:to_acpi_device_node",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583592440,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583594060,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:to_acpi_device_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583605565,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:to_acpi_device_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583741320,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/acpi/fan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/fan.c:to_acpi_device_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583743944,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/acpi/pci_slot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583745149,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/acpi/container.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/container.c:acpi_container_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583808426,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583818526,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584259310,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584306382,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584420992,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585009143,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/ata/libata-zpodd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585033375,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585269775,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585539406,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585631317,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_device_probe",
        "drivers/i2c/i2c-core.c:i2c_new_device",
        "drivers/i2c/i2c-core.c:acpi_i2c_add_device",
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
        "drivers/i2c/i2c-core.c:i2c_register_adapter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585967352,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:399",
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
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool is_acpi_device_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583483453,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583505155,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "addr": 18446744071583550717,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583632809,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583651664,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/pci/pcie/portdrv_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583675743,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583871858,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:to_acpi_device_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583880136,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_companion_match"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583880748,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:to_acpi_device_node"
      ]
    },
    {
      "addr": 18446744071583915047,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583917058,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:to_acpi_device_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583928832,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:to_acpi_device_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584065819,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/fan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/fan.c:acpi_fan_probe"
      ]
    },
    {
      "addr": 18446744071584068346,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/pci_slot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584069569,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/processor_driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584084597,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/container.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/container.c:acpi_container_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584134691,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "addr": 18446744071584142505,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_request_chan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584145374,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584600358,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584629550,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "addr": 18446744071584653046,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584756784,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585380957,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/ata/libata-zpodd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585416976,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585665549,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585933211,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586045021,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "addr": 18446744071583880748,
      "name": "is_acpi_device_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071584065819,
      "name": "is_acpi_device_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
bool is_acpi_device_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583616365,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583623533,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583645082,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583658719,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "addr": 18446744071583687261,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595654803,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583770137,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583789328,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/pci/pcie/portdrv_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583813951,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584010910,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_pm.c:to_acpi_device_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584019190,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_companion_match"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584019821,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:to_acpi_device_node"
      ]
    },
    {
      "addr": 18446744071584055935,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584057954,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:to_acpi_device_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584070027,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:to_acpi_device_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584208268,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/fan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/fan.c:acpi_fan_probe"
      ]
    },
    {
      "addr": 18446744071584210831,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/pci_slot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584212101,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/processor_driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584227183,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/acpi/container.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/container.c:acpi_container_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584282691,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "addr": 18446744071584323033,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_request_chan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584325950,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584781798,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584814686,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "addr": 18446744071584839078,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584930941,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/base/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584947008,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585581789,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/ata/libata-zpodd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585617888,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585853245,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586121563,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586242514,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
        "drivers/i2c/i2c-core.c:i2c_unregister_device",
        "drivers/i2c/i2c-core.c:i2c_new_device",
        "drivers/i2c/i2c-core.c:i2c_device_probe",
        "drivers/i2c/i2c-core.c:i2c_acpi_match_device",
        "drivers/i2c/i2c-core.c:i2c_acpi_match_adapter",
        "drivers/i2c/i2c-core.c:i2c_acpi_find_bus_speed",
        "drivers/i2c/i2c-core.c:i2c_acpi_find_bus_speed",
        "drivers/i2c/i2c-core.c:i2c_acpi_get_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586581608,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:401",
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
      "addr": 18446744071584019821,
      "name": "is_acpi_device_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071584208268,
      "name": "is_acpi_device_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
  "name": "is_acpi_device_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579813523,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583655533,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583658238,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583698815,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583811849,
      "name": "is_acpi_device_node",
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
      "addr": 18446744071583832657,
      "name": "is_acpi_device_node",
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
      "addr": 18446744071583856912,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584065692,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
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
      "name": "is_acpi_device_node",
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
      "addr": 18446744071584074035,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/acpi/glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/glue.c:acpi_platform_notify_remove",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584116700,
      "name": "is_acpi_device_node",
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
      "addr": 18446744071584118716,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
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
      "addr": 18446744071584134517,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/acpi/fan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/fan.c:acpi_fan_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584280563,
      "name": "is_acpi_device_node",
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
      "addr": 18446744071584282163,
      "name": "is_acpi_device_node",
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
      "addr": 18446744071584299603,
      "name": "is_acpi_device_node",
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
      "addr": 18446744071584360691,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
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
      "addr": 18446744071584403193,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_request_chan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584405912,
      "name": "is_acpi_device_node",
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
      "addr": 18446744071584493839,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584870189,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584907399,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
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
      "addr": 18446744071584928800,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585015469,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/base/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:platform_get_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585032448,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
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
      "addr": 18446744071585096540,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/base/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dma-mapping.c:dma_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585269789,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/mfd-core.c:mfd_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585665258,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
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
      "name": "is_acpi_device_node",
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
      "addr": 18446744071585701664,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
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
      "name": "is_acpi_device_node",
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
      "addr": 18446744071585939519,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586209766,
      "name": "is_acpi_device_node",
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
      "addr": 18446744071586312240,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
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
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_adapter",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586346184,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586348444,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/i2c/busses/i2c-designware-baytrail.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586706600,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_add_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586810412,
      "name": "is_acpi_device_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:404",
      "file": "drivers/platform/x86/silead_dmi.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584408693,
      "name": "is_acpi_device_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1299",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_device_is_available",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
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
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pciehp_is_native",
        "drivers/pci/pci-acpi.c:pci_get_hp_params",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup",
        "drivers/acpi/bus.c:acpi_companion_match",
        "drivers/acpi/glue.c:acpi_platform_notify_remove",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start",
        "drivers/acpi/container.c:acpi_container_offline",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/amd_iommu.c:get_irq_domain",
        "drivers/iommu/amd_iommu.c:get_irq_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:get_alias",
        "drivers/iommu/amd_iommu.c:get_alias",
        "drivers/iommu/intel-iommu.c:device_to_iommu",
        "drivers/iommu/intel-iommu.c:device_to_iommu",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported",
        "drivers/base/property.c:device_get_next_child_node",
        "drivers/base/dma-mapping.c:dma_configure",
        "drivers/base/dma-mapping.c:dma_configure",
        "drivers/base/dma-mapping.c:dma_configure",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
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
        "drivers/ata/libata-acpi.c:ata_dev_acpi_handle",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/spi/spi.c:spi_acpi_device_match",
        "drivers/spi/spi.c:spi_acpi_controller_match",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584406656,
      "name": "is_acpi_device_node",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584629749,
      "name": "is_acpi_device_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1307",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
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
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pci_get_hp_params",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup",
        "drivers/acpi/bus.c:acpi_companion_match",
        "drivers/acpi/glue.c:acpi_platform_notify_remove",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start",
        "drivers/acpi/container.c:acpi_container_offline",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:get_alias",
        "drivers/iommu/amd_iommu.c:get_alias",
        "drivers/iommu/intel-iommu.c:device_to_iommu",
        "drivers/iommu/intel-iommu.c:device_to_iommu",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/base/property.c:fwnode_irq_get",
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported",
        "drivers/base/property.c:device_get_next_child_node",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
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
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/spi/spi.c:spi_acpi_device_match",
        "drivers/spi/spi.c:spi_acpi_controller_match",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support",
        "drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe",
        "drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe",
        "drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584630208,
      "name": "is_acpi_device_node",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584731133,
      "name": "is_acpi_device_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1348",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pci_get_hp_params",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup",
        "drivers/acpi/bus.c:acpi_companion_match",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start",
        "drivers/acpi/container.c:acpi_container_offline",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:get_alias",
        "drivers/iommu/intel-iommu.c:device_to_iommu",
        "drivers/iommu/intel-iommu.c:device_to_iommu",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/base/property.c:fwnode_irq_get",
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported",
        "drivers/base/property.c:device_get_next_child_node",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
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
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/spi/spi.c:spi_acpi_device_match",
        "drivers/spi/spi.c:spi_acpi_controller_match",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584728880,
      "name": "is_acpi_device_node",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584933781,
      "name": "is_acpi_device_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1374",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_device_is_available",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup",
        "drivers/acpi/bus.c:acpi_companion_match",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start",
        "drivers/acpi/container.c:acpi_container_offline",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:get_alias",
        "drivers/iommu/intel-iommu.c:device_to_iommu",
        "drivers/iommu/intel-iommu.c:device_to_iommu",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/base/platform.c:platform_get_irq",
        "drivers/base/property.c:fwnode_irq_get",
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported",
        "drivers/base/property.c:device_get_next_child_node",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
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
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/spi/spi.c:spi_acpi_device_match",
        "drivers/spi/spi.c:spi_acpi_controller_match",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "drivers/soundwire/bus.c:sdw_add_bus_master",
        "drivers/soundwire/slave.c:sdw_acpi_find_slaves"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584930720,
      "name": "is_acpi_device_node",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585069589,
      "name": "is_acpi_device_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1374",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_device_is_available",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup",
        "drivers/acpi/bus.c:acpi_companion_match",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start",
        "drivers/acpi/container.c:acpi_container_offline",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/intel-iommu.c:device_to_iommu",
        "drivers/iommu/intel-iommu.c:device_to_iommu",
        "drivers/base/core.c:device_match_acpi_dev",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/property.c:fwnode_irq_get",
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported",
        "drivers/base/property.c:device_get_next_child_node",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
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
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/spi/spi.c:spi_acpi_controller_match",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585066528,
      "name": "is_acpi_device_node",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585774718,
      "name": "is_acpi_device_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1422",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_regions",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/pci-label.c:acpi_index_string_exist",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup",
        "drivers/acpi/bus.c:acpi_device_get_match_data",
        "drivers/acpi/bus.c:acpi_companion_match",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/acpi/evged.c:ged_probe",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start",
        "drivers/acpi/container.c:acpi_container_offline",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:acpi_serdev_check_resources",
        "drivers/iommu/amd/iommu.c:get_devid",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/base/core.c:device_match_acpi_dev",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/property.c:fwnode_irq_get",
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported",
        "drivers/base/property.c:device_get_next_child_node",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_push_id",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_dissociate",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/spi/spi.c:spi_acpi_controller_match",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585771616,
      "name": "is_acpi_device_node",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585893022,
      "name": "is_acpi_device_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1437",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_regions",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/pci-label.c:acpi_index_string_exist",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup",
        "drivers/acpi/bus.c:acpi_device_get_match_data",
        "drivers/acpi/bus.c:acpi_companion_match",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/acpi/evged.c:ged_probe",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start",
        "drivers/acpi/container.c:acpi_container_offline",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:acpi_serdev_check_resources",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/base/core.c:device_match_acpi_dev",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity_release",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/property.c:fwnode_irq_get",
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported",
        "drivers/base/property.c:device_get_next_child_node",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_push_id",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_dissociate",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/spi/spi.c:spi_acpi_controller_match",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585889952,
      "name": "is_acpi_device_node",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585770046,
      "name": "is_acpi_device_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1416",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/pci-label.c:acpi_attr_is_visible",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup",
        "drivers/acpi/bus.c:acpi_device_get_match_data",
        "drivers/acpi/bus.c:acpi_companion_match",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/acpi/evged.c:ged_probe",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start",
        "drivers/acpi/container.c:acpi_container_offline",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/base/core.c:device_match_acpi_dev",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity_release",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/property.c:fwnode_irq_get",
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported",
        "drivers/base/property.c:device_get_next_child_node",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_dissociate",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device",
        "drivers/spi/spi.c:spi_acpi_controller_match",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_get_tgl_lpm_reqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585766992,
      "name": "is_acpi_device_node",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586252958,
      "name": "is_acpi_device_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1411",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pci_dev_acpi_reset",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/pci-label.c:acpi_attr_is_visible",
        "drivers/acpi/device_pm.c:acpi_storage_d3",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup",
        "drivers/acpi/bus.c:acpi_device_get_match_data",
        "drivers/acpi/bus.c:acpi_companion_match",
        "drivers/acpi/glue.c:acpi_device_notify_remove",
        "drivers/acpi/glue.c:acpi_device_notify",
        "drivers/acpi/glue.c:acpi_device_notify",
        "drivers/acpi/glue.c:acpi_device_notify",
        "drivers/acpi/glue.c:acpi_device_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/acpi/evged.c:ged_probe",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/fan.c:acpi_fan_remove",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start",
        "drivers/acpi/container.c:acpi_container_offline",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/base/core.c:device_match_acpi_dev",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity_release",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/property.c:fwnode_irq_get",
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_dissociate",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device",
        "drivers/spi/spi.c:spi_acpi_controller_match",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_dev_set_name",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_get_tgl_lpm_reqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586249968,
      "name": "is_acpi_device_node",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587496179,
      "name": "is_acpi_device_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1448",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_fwnode_device_get_dma_attr",
        "drivers/acpi/property.c:acpi_fwnode_device_dma_supported",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pci/pci.c:pci_pr3_present",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/pcie/edr.c:pci_acpi_remove_edr_notifier",
        "drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier",
        "drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_bridge_d3",
        "drivers/pci/pci-acpi.c:acpi_pci_bridge_d3",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pci_dev_acpi_reset",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/pci-label.c:acpi_attr_is_visible",
        "drivers/pci/vgaarb.c:vga_is_boot_device",
        "drivers/acpi/device_pm.c:acpi_dev_state_d0",
        "drivers/acpi/device_pm.c:acpi_storage_d3",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup",
        "drivers/acpi/bus.c:acpi_device_get_match_data",
        "drivers/acpi/bus.c:acpi_companion_match",
        "drivers/acpi/glue.c:acpi_device_notify_remove",
        "drivers/acpi/glue.c:acpi_device_notify",
        "drivers/acpi/glue.c:acpi_device_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/acpi/evged.c:ged_probe",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/x86/utils.c:acpi_quirk_skip_serdev_enumeration",
        "drivers/acpi/fan_core.c:acpi_fan_remove",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start",
        "drivers/acpi/container.c:acpi_container_offline",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/reset/core.c:__device_reset",
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/iommu.c:check_device",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/base/core.c:device_match_acpi_handle",
        "drivers/base/core.c:device_match_acpi_dev",
        "drivers/base/platform.c:platform_dma_configure",
        "drivers/base/platform.c:platform_dma_configure",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity_release",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/physical_location.c:dev_add_physical_location",
        "drivers/base/physical_location.c:dev_add_physical_location",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_dissociate",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_dev_acpi_handle",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/spi/spi.c:spi_acpi_controller_match",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:acpi_spi_device_alloc",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_dev_set_name",
        "drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register",
        "drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register",
        "drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_unregister_device",
        "drivers/i2c/i2c-core-base.c:i2c_unregister_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_waive_d0_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_get_tgl_lpm_reqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587489920,
      "name": "is_acpi_device_node",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588767475,
      "name": "is_acpi_device_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1619",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_fwnode_device_get_dma_attr",
        "drivers/acpi/property.c:acpi_fwnode_device_dma_supported",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_dev_init",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pci/pci.c:pci_pr3_present",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/pcie/edr.c:pci_acpi_remove_edr_notifier",
        "drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier",
        "drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_bridge_d3",
        "drivers/pci/pci-acpi.c:acpi_pci_bridge_d3",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pci_dev_acpi_reset",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/pci-label.c:acpi_attr_is_visible",
        "drivers/pci/vgaarb.c:vga_is_boot_device",
        "drivers/acpi/device_pm.c:acpi_dev_state_d0",
        "drivers/acpi/device_pm.c:acpi_storage_d3",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup",
        "drivers/acpi/bus.c:acpi_driver_match_device",
        "drivers/acpi/bus.c:acpi_device_get_match_data",
        "drivers/acpi/bus.c:acpi_companion_match",
        "drivers/acpi/glue.c:acpi_device_notify_remove",
        "drivers/acpi/glue.c:acpi_device_notify",
        "drivers/acpi/glue.c:acpi_device_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/acpi/evged.c:ged_probe",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/x86/utils.c:acpi_quirk_skip_serdev_enumeration",
        "drivers/acpi/fan_core.c:acpi_fan_remove",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start",
        "drivers/acpi/container.c:acpi_container_offline",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/reset/core.c:__device_reset",
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/iommu.c:check_device",
        "drivers/iommu/amd/iommu.c:rlookup_amd_iommu",
        "drivers/iommu/amd/iommu.c:rlookup_amd_iommu",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/base/core.c:device_match_acpi_handle",
        "drivers/base/core.c:device_match_acpi_dev",
        "drivers/base/platform.c:platform_dma_configure",
        "drivers/base/platform.c:platform_dma_configure",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity_release",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/physical_location.c:dev_add_physical_location",
        "drivers/base/physical_location.c:dev_add_physical_location",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_dissociate",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_dev_acpi_handle",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/spi/spi.c:spi_acpi_controller_match",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:acpi_spi_device_alloc",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_dev_set_name",
        "drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register",
        "drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register",
        "drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_unregister_device",
        "drivers/i2c/i2c-core-base.c:i2c_unregister_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_waive_d0_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588759616,
      "name": "is_acpi_device_node",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589054675,
      "name": "is_acpi_device_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1607",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_fwnode_device_get_dma_attr",
        "drivers/acpi/property.c:acpi_fwnode_device_dma_supported",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pci/pci.c:pci_pr3_present",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/pcie/edr.c:pci_acpi_remove_edr_notifier",
        "drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier",
        "drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_config_space_access",
        "drivers/pci/pci-acpi.c:acpi_pci_bridge_d3",
        "drivers/pci/pci-acpi.c:acpi_pci_bridge_d3",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pci_dev_acpi_reset",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/pci-label.c:acpi_attr_is_visible",
        "drivers/pci/vgaarb.c:vga_is_boot_device",
        "drivers/acpi/device_pm.c:acpi_dev_state_d0",
        "drivers/acpi/device_pm.c:acpi_storage_d3",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup",
        "drivers/acpi/bus.c:acpi_driver_match_device",
        "drivers/acpi/bus.c:acpi_device_get_match_data",
        "drivers/acpi/bus.c:acpi_companion_match",
        "drivers/acpi/glue.c:acpi_device_notify_remove",
        "drivers/acpi/glue.c:acpi_device_notify",
        "drivers/acpi/glue.c:acpi_device_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/acpi/evged.c:ged_probe",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/x86/utils.c:acpi_quirk_skip_serdev_enumeration",
        "drivers/acpi/fan_core.c:acpi_fan_remove",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start",
        "drivers/acpi/container.c:acpi_container_offline",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/reset/core.c:__device_reset",
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/iommu.c:rlookup_amd_iommu",
        "drivers/iommu/amd/iommu.c:rlookup_amd_iommu",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/base/core.c:device_match_acpi_handle",
        "drivers/base/core.c:device_match_acpi_dev",
        "drivers/base/platform.c:platform_dma_configure",
        "drivers/base/platform.c:platform_dma_configure",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity_release",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/physical_location.c:dev_add_physical_location",
        "drivers/base/physical_location.c:dev_add_physical_location",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_dissociate",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_dev_acpi_handle",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/spi/spi.c:spi_acpi_controller_match",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:acpi_spi_device_alloc",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_dev_set_name",
        "drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register",
        "drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register",
        "drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_unregister_device",
        "drivers/i2c/i2c-core-base.c:i2c_unregister_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_waive_d0_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589048416,
      "name": "is_acpi_device_node",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589360067,
      "name": "is_acpi_device_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1675",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_fwnode_device_get_dma_attr",
        "drivers/acpi/property.c:acpi_fwnode_device_dma_supported",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_parse_string_ref",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pci/pci.c:pci_pr3_present",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/pcie/edr.c:pci_acpi_remove_edr_notifier",
        "drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier",
        "drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_config_space_access",
        "drivers/pci/pci-acpi.c:acpi_pci_bridge_d3",
        "drivers/pci/pci-acpi.c:acpi_pci_bridge_d3",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pci_dev_acpi_reset",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/pci-label.c:acpi_attr_is_visible",
        "drivers/pci/vgaarb.c:vga_is_boot_device",
        "drivers/acpi/device_pm.c:acpi_dev_state_d0",
        "drivers/acpi/device_pm.c:acpi_storage_d3",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup",
        "drivers/acpi/bus.c:acpi_driver_match_device",
        "drivers/acpi/bus.c:acpi_device_get_match_data",
        "drivers/acpi/bus.c:acpi_companion_match",
        "drivers/acpi/glue.c:acpi_device_notify_remove",
        "drivers/acpi/glue.c:acpi_device_notify",
        "drivers/acpi/glue.c:acpi_device_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/acpi/evged.c:ged_probe",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/x86/utils.c:acpi_quirk_skip_serdev_enumeration",
        "drivers/acpi/ac.c:acpi_ac_probe",
        "drivers/acpi/fan_core.c:acpi_fan_remove",
        "drivers/acpi/fan_core.c:acpi_fan_probe",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start",
        "drivers/acpi/container.c:acpi_container_offline",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtcrc.c:intel_chtcrc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/reset/core.c:__device_reset",
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/iommu.c:rlookup_amd_iommu",
        "drivers/iommu/amd/iommu.c:rlookup_amd_iommu",
        "drivers/iommu/intel/iommu.c:device_lookup_iommu",
        "drivers/iommu/intel/iommu.c:device_lookup_iommu",
        "drivers/base/core.c:device_match_acpi_handle",
        "drivers/base/core.c:device_match_acpi_dev",
        "drivers/base/platform.c:platform_dma_configure",
        "drivers/base/platform.c:platform_dma_configure",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity_release",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/physical_location.c:dev_add_physical_location",
        "drivers/base/physical_location.c:dev_add_physical_location",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_on_devcfg",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_set_state",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_acpi_on_resume",
        "drivers/ata/libata-acpi.c:ata_dev_get_GTF",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_dissociate",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_dev",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_acpi_bind_port",
        "drivers/ata/libata-acpi.c:ata_dev_acpi_handle",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/gpu/drm/drm_sysfs.c:drm_connector_acpi_find_companion",
        "drivers/spi/spi.c:spi_acpi_controller_match",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:acpi_spi_device_alloc",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_dev_set_name",
        "drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register",
        "drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register",
        "drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_unregister_device",
        "drivers/i2c/i2c-core-base.c:i2c_unregister_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_waive_d0_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "drivers/platform/x86/amd/wbrf.c:amd_wbrf_retrieve_freq_band",
        "drivers/platform/x86/amd/wbrf.c:acpi_amd_wbrf_supported_consumer",
        "drivers/platform/x86/amd/wbrf.c:acpi_amd_wbrf_supported_producer",
        "drivers/platform/x86/amd/wbrf.c:acpi_amd_wbrf_add_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589353616,
      "name": "is_acpi_device_node",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497473632,
      "name": "is_acpi_device_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1374",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_device_is_available",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/irqchip/irq-mbigen.c:mbigen_device_probe",
        "drivers/irqchip/irq-mbigen.c:mbigen_domain_translate",
        "drivers/irqchip/qcom-irq-combiner.c:combiner_probe",
        "drivers/irqchip/qcom-irq-combiner.c:combiner_probe",
        "drivers/irqchip/qcom-irq-combiner.c:combiner_irq_translate",
        "drivers/bus/hisi_lpc.c:hisi_lpc_remove",
        "drivers/bus/hisi_lpc.c:hisi_lpc_probe",
        "drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe",
        "drivers/bus/hisi_lpc.c:hisi_lpc_acpi_remove",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup",
        "drivers/acpi/bus.c:acpi_companion_match",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/evged.c:ged_probe",
        "drivers/acpi/evged.c:acpi_ged_request_interrupt",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start",
        "drivers/acpi/container.c:acpi_container_offline",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/base/core.c:device_match_acpi_dev",
        "drivers/base/property.c:fwnode_irq_get",
        "drivers/base/property.c:fwnode_irq_get",
        "drivers/base/property.c:device_get_next_child_node",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/mfd-core.c:mfd_add_device",
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
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/spi/spi.c:spi_acpi_controller_match",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:spi_unregister_device",
        "drivers/spi/spi.c:spi_unregister_device",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func",
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe",
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe",
        "drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe_cluster",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497470184,
      "name": "is_acpi_device_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584999077,
      "name": "is_acpi_device_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1374",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_device_is_available",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup",
        "drivers/acpi/bus.c:acpi_companion_match",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start",
        "drivers/acpi/container.c:acpi_container_offline",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/intel-iommu.c:device_to_iommu",
        "drivers/iommu/intel-iommu.c:device_to_iommu",
        "drivers/base/core.c:device_match_acpi_dev",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/property.c:fwnode_irq_get",
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported",
        "drivers/base/property.c:device_get_next_child_node",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/mfd-core.c:mfd_add_device",
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
        "drivers/spi/spi.c:spi_acpi_controller_match",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584996016,
      "name": "is_acpi_device_node",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584914661,
      "name": "is_acpi_device_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1374",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_device_is_available",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup",
        "drivers/acpi/bus.c:acpi_companion_match",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start",
        "drivers/acpi/container.c:acpi_container_offline",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/intel-iommu.c:device_to_iommu",
        "drivers/iommu/intel-iommu.c:device_to_iommu",
        "drivers/base/core.c:device_match_acpi_dev",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/property.c:fwnode_irq_get",
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported",
        "drivers/base/property.c:device_get_next_child_node",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/mfd-core.c:mfd_add_device",
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
        "drivers/spi/spi.c:spi_acpi_controller_match",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584911600,
      "name": "is_acpi_device_node",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585021173,
      "name": "is_acpi_device_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1374",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_device_is_available",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup",
        "drivers/acpi/bus.c:acpi_companion_match",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start",
        "drivers/acpi/container.c:acpi_container_offline",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/intel-iommu.c:device_to_iommu",
        "drivers/iommu/intel-iommu.c:device_to_iommu",
        "drivers/base/core.c:device_match_acpi_dev",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/property.c:fwnode_irq_get",
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported",
        "drivers/base/property.c:device_get_next_child_node",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
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
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/spi/spi.c:spi_acpi_controller_match",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe",
        "drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe",
        "drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585018112,
      "name": "is_acpi_device_node",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_device_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585127349,
      "name": "is_acpi_device_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1374",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_device_is_available",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_find_gpio",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/pci-driver.c:pci_dma_configure",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_resources",
        "drivers/pci/pci-acpi.c:pci_acpi_cleanup",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_find_companion",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_refresh_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_get_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_set_power_state",
        "drivers/pci/pci-acpi.c:acpi_pci_power_manageable",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware",
        "drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_get_bridge_handle",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/acpi/device_pm.c:acpi_dev_pm_attach",
        "drivers/acpi/device_pm.c:acpi_dev_pm_detach",
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup",
        "drivers/acpi/bus.c:acpi_companion_match",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_platform_notify",
        "drivers/acpi/glue.c:acpi_unbind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/glue.c:acpi_bind_one",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_bind",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_poweroff_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_noirq",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr",
        "drivers/acpi/acpi_lpss.c:lpss_reg_read",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/acpi/fan.c:acpi_fan_probe",
        "drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate",
        "drivers/acpi/processor_driver.c:acpi_processor_stop",
        "drivers/acpi/processor_driver.c:acpi_processor_start",
        "drivers/acpi/container.c:acpi_container_offline",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_resume",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_suspend",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_can_wakeup",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources",
        "drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/dmaengine.c:dma_request_chan",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port",
        "drivers/tty/serdev/core.c:serdev_controller_add",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/intel-iommu.c:device_to_iommu",
        "drivers/iommu/intel-iommu.c:device_to_iommu",
        "drivers/base/core.c:device_match_acpi_dev",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/platform.c:__platform_get_irq",
        "drivers/base/property.c:fwnode_irq_get",
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported",
        "drivers/base/property.c:device_get_next_child_node",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/mfd-core.c:mfd_add_device",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe",
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
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/spi/spi.c:spi_acpi_controller_match",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_spi_add_resource",
        "drivers/spi/spi.c:spi_add_device",
        "drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support",
        "drivers/mmc/core/sdio_bus.c:sdio_add_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585124288,
      "name": "is_acpi_device_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
bool is_acpi_device_node(struct fwnode_handle * fwnode)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
bool is_acpi_device_node(struct fwnode_handle * fwnode)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```
</details>
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
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool is_acpi_device_node(const struct fwnode_handle * fwnode)
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
