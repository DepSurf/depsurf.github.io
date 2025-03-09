# Function: <code>devres_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584415680,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:196",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:__devm_request_region",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/memremap.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/devres.c:devm_ioremap",
        "lib/devres.c:devm_ioremap_nocache",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioport_map",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/devres.c:devm_gpiod_get_index",
        "drivers/gpio/devres.c:devm_get_gpiod_from_child",
        "drivers/gpio/devres.c:devm_gpiod_get_array",
        "drivers/gpio/devres.c:devm_gpio_request",
        "drivers/gpio/devres.c:devm_gpio_request_one",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pwm/core.c:devm_of_pwm_get",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/reset/core.c:devm_reset_control_get",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/devres.c:devres_get",
        "drivers/base/devres.c:devres_release",
        "drivers/base/dma-mapping.c:dmam_alloc_noncoherent",
        "drivers/base/dma-mapping.c:dmam_alloc_coherent",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/spi/spi.c:devm_spi_register_master",
        "drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/usb/phy/phy.c:devm_usb_get_phy_dev",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/power/power_supply_core.c:devm_power_supply_register",
        "drivers/power/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_groups",
        "drivers/leds/led-class.c:devm_led_classdev_register",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_add_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev",
        "drivers/extcon/extcon.c:devm_extcon_dev_allocate",
        "drivers/extcon/extcon.c:devm_extcon_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584415680,
      "name": "devres_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584751024,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:196",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/devres.c:devm_ioport_map",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_nocache",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/devres.c:devm_gpio_request_one",
        "drivers/gpio/devres.c:devm_gpio_request",
        "drivers/gpio/devres.c:devm_gpiod_get_array",
        "drivers/gpio/devres.c:devm_get_gpiod_from_child",
        "drivers/gpio/devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/pwm/core.c:devm_of_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/devres.c:devres_release",
        "drivers/base/devres.c:devres_get",
        "drivers/base/dma-mapping.c:dmam_alloc_noncoherent",
        "drivers/base/dma-mapping.c:dmam_alloc_coherent",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/spi/spi.c:devm_spi_register_master",
        "drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size",
        "drivers/usb/phy/phy.c:devm_usb_get_phy_dev",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/power/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/power_supply_core.c:devm_power_supply_register",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_groups",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/leds/led-class.c:devm_led_classdev_register",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/devfreq/devfreq.c:devm_devfreq_register_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_add_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev",
        "drivers/extcon/devres.c:devm_extcon_register_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_register",
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584751024,
      "name": "devres_free",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584941264,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:197",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/devres.c:devm_ioport_map",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_nocache",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/devres.c:devm_gpio_request_one",
        "drivers/gpio/devres.c:devm_gpio_request",
        "drivers/gpio/devres.c:devm_gpiod_get_array",
        "drivers/gpio/devres.c:devm_get_gpiod_from_child",
        "drivers/gpio/devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/pwm/core.c:devm_of_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/devres.c:devres_release",
        "drivers/base/devres.c:devres_get",
        "drivers/base/dma-mapping.c:dmam_alloc_noncoherent",
        "drivers/base/dma-mapping.c:dmam_alloc_coherent",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/spi/spi.c:devm_spi_register_master",
        "drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size",
        "drivers/usb/phy/phy.c:devm_usb_get_phy_dev",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_info",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_groups",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/leds/led-class.c:devm_led_classdev_register",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
        "drivers/devfreq/devfreq.c:devm_devfreq_register_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_add_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev",
        "drivers/extcon/devres.c:devm_extcon_register_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_register",
        "drivers/extcon/devres.c:devm_extcon_dev_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584941264,
      "name": "devres_free",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585025152,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:197",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/devres.c:devm_ioport_map",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register_and_init",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/devres.c:devm_gpio_request_one",
        "drivers/gpio/devres.c:devm_gpio_request",
        "drivers/gpio/devres.c:devm_gpiod_get_array",
        "drivers/gpio/devres.c:devm_fwnode_get_index_gpiod_from_child",
        "drivers/gpio/devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/pwm/core.c:devm_of_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/devres.c:devres_release",
        "drivers/base/devres.c:devres_get",
        "drivers/base/dma-mapping.c:dmam_alloc_attrs",
        "drivers/base/dma-mapping.c:dmam_alloc_coherent",
        "drivers/base/firmware_class.c:assign_firmware_buf",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size",
        "drivers/usb/phy/phy.c:devm_usb_get_phy_dev",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/leds/led-class.c:devm_of_led_classdev_register",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
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
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585025152,
      "name": "devres_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585447760,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:197",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "mm/hmm.c:hmm_devmem_add",
        "lib/devres.c:devm_ioport_map",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register_and_init",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/devres.c:devm_gpio_request_one",
        "drivers/gpio/devres.c:devm_gpio_request",
        "drivers/gpio/devres.c:devm_gpiod_get_array",
        "drivers/gpio/devres.c:devm_fwnode_get_index_gpiod_from_child",
        "drivers/gpio/devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/pwm/core.c:devm_of_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/devres.c:devres_release",
        "drivers/base/devres.c:devres_get",
        "drivers/base/dma-mapping.c:dmam_alloc_attrs",
        "drivers/base/dma-mapping.c:dmam_alloc_coherent",
        "drivers/base/firmware_class.c:assign_firmware_buf",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size",
        "drivers/usb/phy/phy.c:devm_usb_get_phy_dev",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/leds/led-class.c:devm_of_led_classdev_register",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
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
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585447760,
      "name": "devres_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585690992,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:201",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/dma/mapping.c:dmam_alloc_coherent",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "mm/hmm.c:hmm_devmem_add",
        "lib/devres.c:devm_ioport_map",
        "lib/devres.c:__devm_ioremap",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register_and_init",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/devres.c:devm_gpio_request_one",
        "drivers/gpio/devres.c:devm_gpio_request",
        "drivers/gpio/devres.c:devm_gpiod_get_array",
        "drivers/gpio/devres.c:devm_fwnode_get_index_gpiod_from_child",
        "drivers/gpio/devres.c:devm_gpiod_get_from_of_node",
        "drivers/gpio/devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/pwm/core.c:devm_of_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/devres.c:devres_release",
        "drivers/base/devres.c:devres_destroy",
        "drivers/base/devres.c:devres_get",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/rtc/class.c:devm_rtc_device_register",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/leds/led-class.c:devm_of_led_classdev_register",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
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
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585690992,
      "name": "devres_free",
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
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585821920,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:209",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/devres.c:devm_ioport_map",
        "lib/devres.c:__devm_ioremap",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register_and_init",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request_one",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array",
        "drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/pwm/core.c:devm_of_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get_all",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/dma/dmaengine.c:dmaenginem_async_device_register",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/devres.c:devres_release",
        "drivers/base/devres.c:devres_destroy",
        "drivers/base/devres.c:devres_get",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/leds/led-class.c:devm_of_led_classdev_register",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_register",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register",
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
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585821920,
      "name": "devres_free",
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
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586055632,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:209",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/devres.c:devm_ioport_map",
        "lib/devres.c:__devm_ioremap",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register_and_init",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request_one",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array",
        "drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_of_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get_all",
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clkdev.c:devm_clk_hw_register_clkdev",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/dma/dmaengine.c:dmaenginem_async_device_register",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/devres.c:devres_release",
        "drivers/base/devres.c:devres_get",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create",
        "drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/leds/led-class.c:devm_of_led_classdev_register",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_register",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register",
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
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586055632,
      "name": "devres_free",
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
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586203632,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:209",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/devres.c:devm_ioport_map",
        "lib/devres.c:__devm_ioremap",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register_and_init",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request_one",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array",
        "drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_of_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get_all",
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clkdev.c:devm_clk_hw_register_clkdev",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/dma/dmaengine.c:dmaenginem_async_device_register",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/devres.c:devres_release",
        "drivers/base/devres.c:devres_get",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create",
        "drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/leds/led-class.c:devm_led_classdev_register_ext",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_register",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register",
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
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586203632,
      "name": "devres_free",
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
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586966809,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:209",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devres_get",
        "drivers/base/devres.c:devres_get"
      ],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
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
        "drivers/gpio/gpiolib-devres.c:devm_gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request_one",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array",
        "drivers/gpio/gpiolib-devres.c:devm_fwnode_gpiod_get_index",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_of_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get_all",
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clkdev.c:devm_clk_hw_register_clkdev",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/dma/dmaengine.c:dmaenginem_async_device_register",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_np",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create",
        "drivers/net/phy/phy_device.c:devm_phy_package_join",
        "drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
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
      "addr": 18446744071586963792,
      "name": "devres_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587052921,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:225",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devres_get",
        "drivers/base/devres.c:devres_get"
      ],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
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
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_of_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
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
        "drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata",
        "drivers/dma/dmaengine.c:dmaenginem_async_device_register",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_fwnode",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/spi/spi.c:__devm_spi_alloc_controller",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create",
        "drivers/net/phy/mdio_devres.c:__devm_mdiobus_register",
        "drivers/net/phy/mdio_devres.c:devm_mdiobus_alloc_size",
        "drivers/net/phy/phy_device.c:devm_phy_package_join",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
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
      "addr": 18446744071587049120,
      "name": "devres_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586936713,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:225",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devres_get",
        "drivers/base/devres.c:devres_get"
      ],
      "caller_func": [
        "kernel/resource.c:__request_free_mem_region",
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
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
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_of_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
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
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_fwnode",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
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
      "addr": 18446744071586932912,
      "name": "devres_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587499524,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:218",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devm_free_percpu",
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_kfree",
        "drivers/base/devres.c:devm_release_action",
        "drivers/base/devres.c:devm_remove_action",
        "drivers/base/devres.c:devres_get"
      ],
      "caller_func": [
        "kernel/resource.c:__request_free_mem_region",
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
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
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
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
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_fwnode",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
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
      "addr": 18446744071587495232,
      "name": "devres_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588823380,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:218",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devm_free_percpu",
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_kfree",
        "drivers/base/devres.c:devm_release_action",
        "drivers/base/devres.c:devm_remove_action",
        "drivers/base/devres.c:devres_get"
      ],
      "caller_func": [
        "kernel/resource.c:__request_free_mem_region",
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
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
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
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
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/firmware_loader/main.c:fw_add_devm_name",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_fwnode",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/ata/libata-core.c:ata_host_start",
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
      "addr": 18446744071588818656,
      "name": "devres_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590322772,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:223",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devm_free_percpu",
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_kfree",
        "drivers/base/devres.c:devm_release_action",
        "drivers/base/devres.c:devm_remove_action",
        "drivers/base/devres.c:devres_get"
      ],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
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
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
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
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/firmware_loader/main.c:fw_add_devm_name",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_fwnode",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/ata/libata-core.c:ata_host_start",
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
      "addr": 18446744071590317632,
      "name": "devres_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590642692,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:223",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devm_free_percpu",
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_release_action",
        "drivers/base/devres.c:devm_remove_action",
        "drivers/base/devres.c:devres_get"
      ],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
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
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
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
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/firmware_loader/main.c:fw_add_devm_name",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_fwnode",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/ata/libata-core.c:ata_host_start",
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
      "addr": 18446744071590637440,
      "name": "devres_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591002788,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:223",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devm_free_percpu",
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_release_action",
        "drivers/base/devres.c:devm_remove_action",
        "drivers/base/devres.c:devres_get"
      ],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
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
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
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
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/firmware_loader/main.c:fw_add_devm_name",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip_fwnode",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/ata/libata-core.c:ata_host_start",
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
      "addr": 18446744071590997504,
      "name": "devres_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499001696,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:209",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/devres.c:devm_ioport_map",
        "lib/devres.c:__devm_ioremap",
        "drivers/bus/vexpress-config.c:devm_regmap_init_vexpress_config",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register_and_init",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request_one",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array",
        "drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_of_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get_all",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get_optional",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clkdev.c:devm_clk_hw_register_clkdev",
        "drivers/clk/clk.c:devm_of_clk_add_hw_provider",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/dma/dmaengine.c:dmaenginem_async_device_register",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/devres.c:devres_release",
        "drivers/base/devres.c:devres_get",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create",
        "drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size",
        "drivers/usb/phy/phy.c:devm_usb_get_phy_by_node",
        "drivers/usb/phy/phy.c:devm_usb_get_phy_by_node",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register",
        "drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/leds/led-class.c:devm_led_classdev_register_ext",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
        "drivers/firmware/ti_sci.c:devm_ti_sci_get_by_phandle",
        "drivers/firmware/ti_sci.c:devm_ti_sci_get_handle",
        "drivers/of/platform.c:devm_of_platform_populate",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_register",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register",
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
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499001696,
      "name": "devres_free",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231570244,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:209",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/devres.c:__devm_ioremap",
        "drivers/bus/vexpress-config.c:devm_regmap_init_vexpress_config",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register_and_init",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request_one",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array",
        "drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_of_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get_all",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get_optional",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clkdev.c:devm_clk_hw_register_clkdev",
        "drivers/clk/clk.c:devm_of_clk_add_hw_provider",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/dma/dmaengine.c:dmaenginem_async_device_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/devres.c:devres_release",
        "drivers/base/devres.c:devres_get",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create",
        "drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size",
        "drivers/usb/phy/phy.c:devm_usb_get_phy_by_node",
        "drivers/usb/phy/phy.c:devm_usb_get_phy_by_node",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register",
        "drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/leds/led-class.c:devm_led_classdev_register_ext",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
        "drivers/of/platform.c:devm_of_platform_populate",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_register",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register",
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
        "sound/soc/soc-jack.c:snd_soc_jack_add_gpios",
        "sound/soc/soc-devres.c:devm_snd_dmaengine_pcm_register",
        "sound/soc/soc-devres.c:devm_snd_soc_register_card",
        "sound/soc/soc-devres.c:devm_snd_soc_register_component",
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231570244,
      "name": "devres_free",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292165448,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:209",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devres_release",
        "drivers/base/devres.c:devres_destroy",
        "drivers/base/devres.c:devres_get"
      ],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/devres.c:devm_ioport_map",
        "lib/devres.c:__devm_ioremap",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register_and_init",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request_one",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array",
        "drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_of_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/dma/dmaengine.c:dmaenginem_async_device_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/devres.c:devres_release",
        "drivers/base/devres.c:devres_destroy",
        "drivers/base/devres.c:devres_get",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create",
        "drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size",
        "drivers/usb/phy/phy.c:devm_usb_get_phy_by_node",
        "drivers/usb/phy/phy.c:devm_usb_get_phy_by_node",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register",
        "drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/leds/led-class.c:devm_led_classdev_register_ext",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
        "drivers/of/platform.c:devm_of_platform_populate",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_register",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register",
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
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292164336,
      "name": "devres_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 13835058055292164416,
      "name": "devres_free",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276376432,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:209",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/devres.c:__devm_ioremap",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register_and_init",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request_one",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array",
        "drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_of_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get_all",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get_optional",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clkdev.c:devm_clk_hw_register_clkdev",
        "drivers/clk/clk.c:devm_of_clk_add_hw_provider",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/dma/dmaengine.c:dmaenginem_async_device_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/devres.c:devres_release",
        "drivers/base/devres.c:devres_get",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create",
        "drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size",
        "drivers/usb/phy/phy.c:devm_usb_get_phy_by_node",
        "drivers/usb/phy/phy.c:devm_usb_get_phy_by_node",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register",
        "drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/leds/led-class.c:devm_led_classdev_register_ext",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
        "drivers/of/platform.c:devm_of_platform_populate",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_register",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register",
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
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276376432,
      "name": "devres_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585963840,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:209",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/devres.c:devm_ioport_map",
        "lib/devres.c:__devm_ioremap",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register_and_init",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request_one",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array",
        "drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_of_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get_all",
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clkdev.c:devm_clk_hw_register_clkdev",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/dma/dmaengine.c:dmaenginem_async_device_register",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/devres.c:devres_release",
        "drivers/base/devres.c:devres_get",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create",
        "drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_register",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register",
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
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585963840,
      "name": "devres_free",
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
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585813104,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:209",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/irq/irq_sim.c:devm_irq_sim_init",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/devres.c:devm_ioport_map",
        "lib/devres.c:__devm_ioremap",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register_and_init",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request_one",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array",
        "drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get_all",
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clkdev.c:devm_clk_hw_register_clkdev",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/dma/dmaengine.c:dmaenginem_async_device_register",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/devres.c:devres_release",
        "drivers/base/devres.c:devres_get",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create",
        "drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_register",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register",
        "drivers/devfreq/devfreq.c:devm_devfreq_register_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_add_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_add_edev",
        "drivers/nvmem/core.c:devm_nvmem_cell_get",
        "drivers/nvmem/core.c:devm_nvmem_device_get",
        "drivers/nvmem/core.c:devm_nvmem_register",
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585813104,
      "name": "devres_free",
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
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586153648,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:209",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/devres.c:devm_ioport_map",
        "lib/devres.c:__devm_ioremap",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register_and_init",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request_one",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array",
        "drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_of_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get_all",
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clkdev.c:devm_clk_hw_register_clkdev",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/dma/dmaengine.c:dmaenginem_async_device_register",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/devres.c:devres_release",
        "drivers/base/devres.c:devres_get",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create",
        "drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/leds/led-class.c:devm_led_classdev_register_ext",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_register",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register",
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
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586153648,
      "name": "devres_free",
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
void devres_free(void * res)
```

```json
{
  "name": "devres_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586262352,
      "name": "devres_free",
      "external": true,
      "loc": "drivers/base/devres.c:209",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "kernel/resource.c:devm_request_resource",
        "kernel/reboot.c:devm_register_reboot_notifier",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/devres.c:devm_request_any_context_irq",
        "kernel/irq/devres.c:devm_request_threaded_irq",
        "kernel/dma/mapping.c:dmam_alloc_attrs",
        "kernel/iomem.c:devm_memremap",
        "mm/dmapool.c:dmam_pool_create",
        "lib/devres.c:devm_ioport_map",
        "lib/devres.c:__devm_ioremap",
        "drivers/phy/phy-core.c:__devm_of_phy_provider_register",
        "drivers/phy/phy-core.c:devm_phy_create",
        "drivers/phy/phy-core.c:devm_of_phy_get_by_index",
        "drivers/phy/phy-core.c:devm_of_phy_get",
        "drivers/phy/phy-core.c:devm_phy_get",
        "drivers/pinctrl/core.c:devm_pinctrl_register_and_init",
        "drivers/pinctrl/core.c:devm_pinctrl_register",
        "drivers/pinctrl/core.c:devm_pinctrl_get",
        "drivers/gpio/gpiolib.c:devm_gpiochip_add_data",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request_one",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_request",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_array",
        "drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:devm_of_pwm_get",
        "drivers/pwm/core.c:devm_pwm_get",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:devm_pci_remap_iospace",
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create",
        "drivers/video/backlight/backlight.c:devm_backlight_device_register",
        "drivers/clk/clk-devres.c:devm_get_clk_from_child",
        "drivers/clk/clk-devres.c:devm_clk_bulk_get_all",
        "drivers/clk/clk-devres.c:__devm_clk_bulk_get",
        "drivers/clk/clk-devres.c:devm_clk_get",
        "drivers/clk/clkdev.c:devm_clk_hw_register_clkdev",
        "drivers/clk/clk.c:devm_clk_hw_register",
        "drivers/clk/clk.c:devm_clk_register",
        "drivers/dma/dmaengine.c:dmaenginem_async_device_register",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_register",
        "drivers/regulator/devres.c:devm_regulator_register_notifier",
        "drivers/regulator/devres.c:devm_regulator_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_register",
        "drivers/regulator/devres.c:devm_regulator_bulk_get",
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/reset/core.c:devm_reset_control_array_get",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:devm_reset_controller_register",
        "drivers/tty/serdev/core.c:devm_serdev_device_open",
        "drivers/char/hw_random/core.c:devm_hwrng_register",
        "drivers/base/core.c:devm_device_add_groups",
        "drivers/base/core.c:devm_device_add_group",
        "drivers/base/devres.c:devres_release",
        "drivers/base/devres.c:devres_get",
        "drivers/base/regmap/regmap.c:__devm_regmap_init",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/spi/spi.c:devm_spi_register_controller",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_create",
        "drivers/net/phy/mdio_bus.c:devm_mdiobus_alloc_size",
        "drivers/usb/phy/phy.c:devm_usb_get_phy",
        "drivers/input/input.c:input_register_device",
        "drivers/input/input.c:devm_input_allocate_device",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register_no_ws",
        "drivers/power/supply/power_supply_core.c:devm_power_supply_register",
        "drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register",
        "drivers/watchdog/watchdog_core.c:devm_watchdog_register_device",
        "drivers/leds/led-class.c:devm_led_classdev_register_ext",
        "drivers/leds/led-triggers.c:devm_led_trigger_register",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_register",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register",
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
        "net/ethernet/eth.c:devm_alloc_etherdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586262352,
      "name": "devres_free",
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
