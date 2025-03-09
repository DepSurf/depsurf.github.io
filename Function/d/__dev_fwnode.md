# Function: <code>__dev_fwnode</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * __dev_fwnode(struct device * dev)
```

```json
{
  "name": "__dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590335381,
      "name": "__dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:20",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_bus_match",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_optional",
        "drivers/gpio/gpiolib.c:gpiod_get",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pci/pci-acpi.c:pci_set_acpi_fwnode",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/dma/lgm/lgm-dma.c:ldma_parse_dt",
        "drivers/iommu/iommu.c:iommu_device_register",
        "drivers/base/core.c:device_match_fwnode",
        "drivers/base/platform.c:__platform_get_irq_byname",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:device_remove_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/net/phy/phy_device.c:device_phy_find_device",
        "drivers/usb/dwc2/drd.c:dwc2_drd_init",
        "drivers/usb/roles/class.c:usb_role_switch_get",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/mmc/core/host.c:mmc_of_parse",
        "drivers/hte/hte.c:hte_ts_get",
        "net/ethernet/eth.c:device_get_ethdev_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590336016,
      "name": "__dev_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct fwnode_handle * __dev_fwnode(struct device * dev)
```

```json
{
  "name": "__dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590655429,
      "name": "__dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:20",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_phy_mode"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_optional",
        "drivers/gpio/gpiolib.c:gpiod_get",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/gpio/gpiolib.c:gpio_bus_match",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pci/pci-acpi.c:pci_set_acpi_fwnode",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/dma/lgm/lgm-dma.c:ldma_parse_dt",
        "drivers/iommu/iommu.c:iommu_device_register",
        "drivers/base/core.c:device_match_fwnode",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:device_remove_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/net/phy/phy_device.c:device_phy_find_device",
        "drivers/usb/dwc2/drd.c:dwc2_drd_init",
        "drivers/usb/roles/class.c:usb_role_switch_get",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/i2c/i2c-core-base.c:i2c_dev_or_parent_fwnode_match",
        "drivers/i2c/i2c-core-base.c:i2c_dev_or_parent_fwnode_match",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/mmc/core/host.c:mmc_of_parse",
        "drivers/hte/hte.c:hte_ts_get",
        "net/ethernet/eth.c:device_get_ethdev_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590656064,
      "name": "__dev_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct fwnode_handle * __dev_fwnode(struct device * dev)
```

```json
{
  "name": "__dev_fwnode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591015733,
      "name": "__dev_fwnode",
      "external": true,
      "loc": "drivers/base/property.c:20",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_phy_mode"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_optional",
        "drivers/gpio/gpiolib.c:gpiod_get",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/gpio/gpiolib.c:gpiochip_add_irqchip",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_setup_dev",
        "drivers/gpio/gpiolib.c:gpio_bus_match",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/pwm/core.c:pwm_get",
        "drivers/pci/pci-acpi.c:pci_set_acpi_fwnode",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/acpi/viot.c:viot_get_iommu",
        "drivers/dma/lgm/lgm-dma.c:ldma_parse_dt",
        "drivers/tty/serdev/core.c:serdev_controller_alloc",
        "drivers/iommu/iommu.c:iommu_device_register",
        "drivers/base/core.c:device_match_fwnode",
        "drivers/base/platform.c:platform_dma_configure",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity_release",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:device_remove_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/regmap/regmap.c:regmap_get_val_endian",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_remove",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_add",
        "drivers/net/phy/phy_device.c:device_phy_find_device",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:mdiobus_release",
        "drivers/usb/dwc2/drd.c:dwc2_drd_init",
        "drivers/usb/roles/class.c:usb_role_switch_get",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/i2c/i2c-core-base.c:i2c_dev_or_parent_fwnode_match",
        "drivers/i2c/i2c-core-base.c:i2c_dev_or_parent_fwnode_match",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "drivers/mmc/core/host.c:mmc_of_parse",
        "drivers/hte/hte.c:hte_ts_get",
        "net/ethernet/eth.c:device_get_ethdev_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591016368,
      "name": "__dev_fwnode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct fwnode_handle * __dev_fwnode(struct device * dev)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
