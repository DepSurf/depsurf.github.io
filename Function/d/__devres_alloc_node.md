# Function: <code>__devres_alloc_node</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void * __devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid, const char * name)
```

```json
{
  "name": "__devres_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587495136,
      "name": "__devres_alloc_node",
      "external": true,
      "loc": "drivers/base/devres.c:157",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_free_mem_region",
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:devm_irq_setup_generic_chip",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/devres.c:pcim_iomap_table",
        "lib/devres.c:devm_ioport_map",
        "lib/devres.c:devm_ioremap_np",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_uc",
        "lib/devres.c:devm_ioremap",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register_and_init",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request_one",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array",
        "drivers/gpio/gpiolib-devres.c:devm_fwnode_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/pci.c:pcim_enable_device",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get_all",
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clkdev.c:devm_clk_hw_register_clkdev",
        "drivers/clk/clk.c:devm_clk_notifier_register",
        "drivers/clk/clk.c:devm_clk_hw_get_clk",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/clk/clk-divider.c:__devm_clk_hw_register_divider",
        "drivers/clk/clk-mux.c:__devm_clk_hw_register_mux",
        "drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata",
        "drivers/dma/dmaengine.c:dmaenginem_async_device_register",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_bulk_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/component.c:__component_match_add",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/base/devres.c:devm_get_free_pages",
        "drivers/base/devres.c:devm_add_action",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_fwnode",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/ata/libata-core.c:ata_host_alloc",
        "drivers/spi/spi.c:__devm_spi_alloc_controller",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create",
        "drivers/net/phy/mdio_devres.c:__devm_mdiobus_register",
        "drivers/net/phy/mdio_devres.c:devm_mdiobus_alloc_size",
        "drivers/net/phy/phy_device.c:devm_phy_package_join",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register",
        "drivers/thermal/thermal_hwmon.c:devm_thermal_add_hwmon_sysfs",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/leds/led-class.c:devm_led_classdev_register_ext",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
        "drivers/platform/x86/intel_scu_ipc.c:__devm_intel_scu_ipc_register",
        "drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_dev_get",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_register",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register",
        "drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc",
        "drivers/devfreq/devfreq.c:devm_devfreq_register_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_add_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev",
        "drivers/extcon/devres.c:devm_extcon_register_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_register_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_register",
        "drivers/extcon/devres.c:devm_extcon_dev_allocate",
        "drivers/nvmem/core.c:devm_nvmem_cell_get",
        "drivers/nvmem/core.c:devm_nvmem_device_get",
        "drivers/nvmem/core.c:devm_nvmem_register",
        "drivers/interconnect/core.c:devm_of_icc_get",
        "net/devres.c:devm_register_netdev",
        "net/devres.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587495136,
      "name": "__devres_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void * __devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid, const char * name)
```

```json
{
  "name": "__devres_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588818528,
      "name": "__devres_alloc_node",
      "external": true,
      "loc": "drivers/base/devres.c:157",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_free_mem_region",
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:devm_irq_setup_generic_chip",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/irq/msi.c:msi_setup_device_data",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/string_helpers.c:devm_kasprintf_strarray",
        "lib/devres.c:devm_arch_io_reserve_memtype_wc",
        "lib/devres.c:devm_arch_phys_wc_add",
        "lib/devres.c:pcim_iomap_table",
        "lib/devres.c:devm_ioport_map",
        "lib/devres.c:devm_ioremap_np",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_uc",
        "lib/devres.c:devm_ioremap",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register_and_init",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request_one",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array",
        "drivers/gpio/gpiolib-devres.c:devm_fwnode_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/pci.c:pcim_enable_device",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get_all",
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clkdev.c:devm_clk_hw_register_clkdev",
        "drivers/clk/clk.c:devm_clk_notifier_register",
        "drivers/clk/clk.c:devm_clk_hw_get_clk",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/clk/clk-divider.c:__devm_clk_hw_register_divider",
        "drivers/clk/clk-gate.c:__devm_clk_hw_register_gate",
        "drivers/clk/clk-mux.c:__devm_clk_hw_register_mux",
        "drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata",
        "drivers/dma/dmaengine.c:dmaenginem_async_device_register",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_bulk_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/component.c:__component_match_add",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/base/devres.c:devm_get_free_pages",
        "drivers/base/devres.c:devm_add_action",
        "drivers/base/firmware_loader/main.c:fw_add_devm_name",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_fwnode",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/ata/libata-core.c:ata_host_start",
        "drivers/ata/libata-core.c:ata_host_alloc",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/spi/spi.c:__devm_spi_alloc_controller",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create",
        "drivers/net/phy/mdio_devres.c:__devm_mdiobus_register",
        "drivers/net/phy/mdio_devres.c:devm_mdiobus_alloc_size",
        "drivers/net/phy/phy_device.c:devm_phy_package_join",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register",
        "drivers/thermal/thermal_hwmon.c:devm_thermal_add_hwmon_sysfs",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/leds/led-class.c:devm_led_classdev_register_ext",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
        "drivers/platform/x86/intel_scu_ipc.c:__devm_intel_scu_ipc_register",
        "drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_dev_get",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_register",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register",
        "drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc",
        "drivers/devfreq/devfreq.c:devm_devfreq_register_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_add_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev",
        "drivers/extcon/devres.c:devm_extcon_register_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_register_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_register",
        "drivers/extcon/devres.c:devm_extcon_dev_allocate",
        "drivers/nvmem/core.c:devm_nvmem_cell_get",
        "drivers/nvmem/core.c:devm_nvmem_device_get",
        "drivers/interconnect/core.c:devm_of_icc_get",
        "net/devres.c:devm_register_netdev",
        "net/devres.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588818528,
      "name": "__devres_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void * __devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid, const char * name)
```

```json
{
  "name": "__devres_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590317456,
      "name": "__devres_alloc_node",
      "external": true,
      "loc": "drivers/base/devres.c:162",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:devm_irq_setup_generic_chip",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/irq/msi.c:msi_setup_device_data",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/string_helpers.c:devm_kasprintf_strarray",
        "lib/devres.c:devm_arch_io_reserve_memtype_wc",
        "lib/devres.c:devm_arch_phys_wc_add",
        "lib/devres.c:pcim_iomap_table",
        "lib/devres.c:devm_ioport_map",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_uc",
        "lib/devres.c:devm_ioremap",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register_and_init",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request_one",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array",
        "drivers/gpio/gpiolib-devres.c:devm_fwnode_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/pci.c:pcim_enable_device",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get_all",
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get",
        "drivers/clk/clk-devres.c:devm_clk_get_optional_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_optional_prepared",
        "drivers/clk/clk-devres.c:devm_clk_get_optional",
        "drivers/clk/clk-devres.c:devm_clk_get_enabled",
        "drivers/clk/clk.c:devm_clk_notifier_register",
        "drivers/clk/clk.c:devm_clk_hw_get_clk",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/clk/clk-divider.c:__devm_clk_hw_register_divider",
        "drivers/clk/clk-fixed-rate.c:__clk_hw_register_fixed_rate",
        "drivers/clk/clk-gate.c:__devm_clk_hw_register_gate",
        "drivers/clk/clk-mux.c:__devm_clk_hw_register_mux",
        "drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata",
        "drivers/dma/dmaengine.c:dmaenginem_async_device_register",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:_devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_bulk_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/component.c:__component_match_add",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/base/devres.c:devm_get_free_pages",
        "drivers/base/devres.c:devm_add_action",
        "drivers/base/firmware_loader/main.c:fw_add_devm_name",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_fwnode",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/ata/libata-core.c:ata_host_start",
        "drivers/ata/libata-core.c:ata_host_alloc",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/spi/spi.c:__devm_spi_alloc_controller",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create",
        "drivers/net/phy/mdio_devres.c:__devm_mdiobus_register",
        "drivers/net/phy/mdio_devres.c:devm_mdiobus_alloc_size",
        "drivers/net/phy/phy_device.c:devm_phy_package_join",
        "drivers/net/pse-pd/pse_core.c:devm_pse_controller_register",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register",
        "drivers/thermal/thermal_hwmon.c:devm_thermal_add_hwmon_sysfs",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/leds/led-class.c:devm_led_classdev_register_ext",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
        "drivers/platform/x86/intel_scu_ipc.c:__devm_intel_scu_ipc_register",
        "drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_dev_get",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_register",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register",
        "drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc",
        "drivers/devfreq/devfreq.c:devm_devfreq_register_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_add_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev",
        "drivers/extcon/devres.c:devm_extcon_register_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_register_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_register",
        "drivers/extcon/devres.c:devm_extcon_dev_allocate",
        "drivers/nvmem/core.c:devm_nvmem_cell_get",
        "drivers/nvmem/core.c:devm_nvmem_device_get",
        "drivers/interconnect/core.c:devm_of_icc_get",
        "drivers/interconnect/bulk.c:devm_of_icc_bulk_get",
        "net/devres.c:devm_register_netdev",
        "net/devres.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590317456,
      "name": "__devres_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void * __devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid, const char * name)
```

```json
{
  "name": "__devres_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590637264,
      "name": "__devres_alloc_node",
      "external": true,
      "loc": "drivers/base/devres.c:162",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:devm_irq_setup_generic_chip",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/irq/msi.c:msi_setup_device_data",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/string_helpers.c:devm_kasprintf_strarray",
        "lib/devres.c:devm_arch_io_reserve_memtype_wc",
        "lib/devres.c:devm_arch_phys_wc_add",
        "lib/devres.c:pcim_iomap_table",
        "lib/devres.c:devm_ioport_map",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_uc",
        "lib/devres.c:devm_ioremap",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_optional_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register_and_init",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request_one",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array",
        "drivers/gpio/gpiolib-devres.c:devm_fwnode_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/pci.c:pcim_enable_device",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get_all",
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get",
        "drivers/clk/clk-devres.c:devm_clk_get_optional_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_optional_prepared",
        "drivers/clk/clk-devres.c:devm_clk_get_optional",
        "drivers/clk/clk-devres.c:devm_clk_get_enabled",
        "drivers/clk/clk.c:devm_clk_notifier_register",
        "drivers/clk/clk.c:devm_clk_hw_get_clk",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/clk/clk-divider.c:__devm_clk_hw_register_divider",
        "drivers/clk/clk-fixed-rate.c:__clk_hw_register_fixed_rate",
        "drivers/clk/clk-gate.c:__devm_clk_hw_register_gate",
        "drivers/clk/clk-mux.c:__devm_clk_hw_register_mux",
        "drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:_devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_bulk_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/component.c:__component_match_add",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/base/devres.c:devm_get_free_pages",
        "drivers/base/devres.c:__devm_add_action",
        "drivers/base/firmware_loader/main.c:fw_add_devm_name",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_fwnode",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/ata/libata-core.c:ata_host_start",
        "drivers/ata/libata-core.c:ata_host_alloc",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/spi/spi.c:__devm_spi_alloc_controller",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create",
        "drivers/net/phy/mdio_devres.c:__devm_mdiobus_register",
        "drivers/net/phy/mdio_devres.c:devm_mdiobus_alloc_size",
        "drivers/net/phy/phy_device.c:devm_phy_package_join",
        "drivers/net/pse-pd/pse_core.c:devm_pse_controller_register",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register",
        "drivers/thermal/thermal_hwmon.c:devm_thermal_add_hwmon_sysfs",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/mmc/core/host.c:devm_mmc_alloc_host",
        "drivers/leds/led-class.c:devm_led_classdev_register_ext",
        "drivers/leds/led-class.c:devm_led_get",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
        "drivers/platform/x86/intel_scu_ipc.c:__devm_intel_scu_ipc_register",
        "drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_dev_get",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_register",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register",
        "drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc",
        "drivers/devfreq/devfreq.c:devm_devfreq_register_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_add_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev",
        "drivers/extcon/devres.c:devm_extcon_register_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_register_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_register",
        "drivers/extcon/devres.c:devm_extcon_dev_allocate",
        "drivers/nvmem/core.c:devm_nvmem_cell_get",
        "drivers/nvmem/core.c:devm_nvmem_device_get",
        "drivers/interconnect/core.c:devm_of_icc_get",
        "drivers/interconnect/bulk.c:devm_of_icc_bulk_get",
        "net/devres.c:devm_register_netdev",
        "net/devres.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590637264,
      "name": "__devres_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void * __devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid, const char * name)
```

```json
{
  "name": "__devres_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590997328,
      "name": "__devres_alloc_node",
      "external": true,
      "loc": "drivers/base/devres.c:162",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:devm_irq_setup_generic_chip",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/irq/msi.c:msi_setup_device_data",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/string_helpers.c:devm_kasprintf_strarray",
        "lib/devres.c:devm_arch_io_reserve_memtype_wc",
        "lib/devres.c:devm_arch_phys_wc_add",
        "lib/devres.c:pcim_iomap_table",
        "lib/devres.c:devm_ioport_map",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_uc",
        "lib/devres.c:devm_ioremap",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_optional_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register_and_init",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request_one",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array",
        "drivers/gpio/gpiolib-devres.c:devm_fwnode_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/pci.c:pcim_enable_device",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get_all",
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get",
        "drivers/clk/clk-devres.c:devm_clk_get_optional_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_optional_prepared",
        "drivers/clk/clk-devres.c:devm_clk_get_optional",
        "drivers/clk/clk-devres.c:devm_clk_get_enabled",
        "drivers/clk/clk.c:devm_clk_notifier_register",
        "drivers/clk/clk.c:devm_clk_hw_get_clk",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/clk/clk-divider.c:__devm_clk_hw_register_divider",
        "drivers/clk/clk-fixed-rate.c:__clk_hw_register_fixed_rate",
        "drivers/clk/clk-gate.c:__devm_clk_hw_register_gate",
        "drivers/clk/clk-mux.c:__devm_clk_hw_register_mux",
        "drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:_devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_bulk_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/component.c:__component_match_add",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/devres.c:__devm_alloc_percpu",
        "drivers/base/devres.c:devm_get_free_pages",
        "drivers/base/devres.c:__devm_add_action",
        "drivers/base/firmware_loader/main.c:fw_add_devm_name",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_fwnode",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/ata/libata-core.c:ata_host_start",
        "drivers/ata/libata-core.c:ata_host_alloc",
        "drivers/gpu/drm/bridge/panel.c:devm_drm_panel_bridge_add_typed",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/spi/spi.c:__devm_spi_alloc_controller",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create",
        "drivers/net/phy/mdio_devres.c:__devm_mdiobus_register",
        "drivers/net/phy/mdio_devres.c:devm_mdiobus_alloc_size",
        "drivers/net/phy/phy_device.c:devm_phy_package_join",
        "drivers/net/pse-pd/pse_core.c:devm_pse_controller_register",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register",
        "drivers/thermal/thermal_hwmon.c:devm_thermal_add_hwmon_sysfs",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/mmc/core/host.c:devm_mmc_alloc_host",
        "drivers/leds/led-class.c:devm_led_classdev_register_ext",
        "drivers/leds/led-class.c:devm_led_get",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
        "drivers/platform/x86/intel_scu_ipc.c:__devm_intel_scu_ipc_register",
        "drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_dev_get",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_register",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register",
        "drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc",
        "drivers/devfreq/devfreq.c:devm_devfreq_register_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_add_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev",
        "drivers/extcon/devres.c:devm_extcon_register_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_register_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_register",
        "drivers/extcon/devres.c:devm_extcon_dev_allocate",
        "drivers/nvmem/core.c:devm_nvmem_cell_get",
        "drivers/nvmem/core.c:devm_nvmem_device_get",
        "drivers/interconnect/core.c:devm_of_icc_get",
        "drivers/interconnect/bulk.c:devm_of_icc_bulk_get",
        "net/devres.c:devm_register_netdev",
        "net/devres.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590997328,
      "name": "__devres_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void * __devres_alloc_node(dr_release_t release, size_t size, gfp_t gfp, int nid, const char * name)
```
</details>
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
