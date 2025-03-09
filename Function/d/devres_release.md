# Function: <code>devres_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584416000,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:393",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_put",
        "drivers/regulator/devres.c:devm_regulator_unregister",
        "drivers/regulator/devres.c:devm_regulator_unregister_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_unregister_notifier",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584416000,
      "name": "devres_release",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584751360,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:393",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:devm_gpiochip_remove",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584751360,
      "name": "devres_release",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584941600,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:394",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:devm_gpiochip_remove",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584941600,
      "name": "devres_release",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585025248,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:394",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/hw_random/core.c:devm_hwrng_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585025248,
      "name": "devres_release",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585447856,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:394",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/hw_random/core.c:devm_hwrng_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585447856,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585691088,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:398",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585691088,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585822240,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:406",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585822240,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586055968,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:406",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_release_resource",
        "kernel/iomem.c:devm_memunmap",
        "mm/dmapool.c:dmam_pool_destroy",
        "drivers/pinctrl/core.c:devm_pinctrl_unregister",
        "drivers/pinctrl/core.c:devm_pinctrl_put",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_free",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios",
        "drivers/pwm/core.c:devm_pwm_put",
        "drivers/clk/clk.c:devm_clk_hw_unregister",
        "drivers/clk/clk.c:devm_clk_unregister",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/base/core.c:devm_device_remove_groups",
        "drivers/base/core.c:devm_device_remove_group",
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_release_action",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_unregister",
        "drivers/leds/led-class.c:devm_led_classdev_unregister",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_unregister",
        "drivers/extcon/devres.c:devm_extcon_dev_free",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586055968,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586203968,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:406",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_release_resource",
        "kernel/iomem.c:devm_memunmap",
        "mm/dmapool.c:dmam_pool_destroy",
        "drivers/pinctrl/core.c:devm_pinctrl_unregister",
        "drivers/pinctrl/core.c:devm_pinctrl_put",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_free",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios",
        "drivers/pwm/core.c:devm_pwm_put",
        "drivers/clk/clk.c:devm_clk_hw_unregister",
        "drivers/clk/clk.c:devm_clk_unregister",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/base/core.c:devm_device_remove_groups",
        "drivers/base/core.c:devm_device_remove_group",
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_release_action",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_unregister",
        "drivers/leds/led-class.c:devm_led_classdev_unregister",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_unregister",
        "drivers/extcon/devres.c:devm_extcon_dev_free",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586203968,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586966192,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:406",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_release_resource",
        "kernel/iomem.c:devm_memunmap",
        "mm/dmapool.c:dmam_pool_destroy",
        "drivers/pinctrl/core.c:devm_pinctrl_unregister",
        "drivers/pinctrl/core.c:devm_pinctrl_put",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_free",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios",
        "drivers/pwm/core.c:devm_pwm_put",
        "drivers/clk/clkdev.c:devm_clk_release_clkdev",
        "drivers/clk/clk.c:devm_clk_hw_unregister",
        "drivers/clk/clk.c:devm_clk_unregister",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free",
        "drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/base/core.c:devm_device_remove_groups",
        "drivers/base/core.c:devm_device_remove_group",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_unregister",
        "drivers/leds/led-class.c:devm_led_classdev_unregister",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_unregister",
        "drivers/extcon/devres.c:devm_extcon_dev_free",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586966192,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587051904,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:422",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_release_resource",
        "kernel/iomem.c:devm_memunmap",
        "mm/dmapool.c:dmam_pool_destroy",
        "drivers/pinctrl/core.c:devm_pinctrl_unregister",
        "drivers/pinctrl/core.c:devm_pinctrl_put",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_free",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios",
        "drivers/pwm/core.c:devm_pwm_put",
        "drivers/clk/clkdev.c:devm_clk_release_clkdev",
        "drivers/clk/clk.c:devm_clk_hw_unregister",
        "drivers/clk/clk.c:devm_clk_unregister",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free",
        "drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/base/core.c:devm_device_remove_groups",
        "drivers/base/core.c:devm_device_remove_group",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_unregister",
        "drivers/leds/led-class.c:devm_led_classdev_unregister",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_unregister",
        "drivers/extcon/devres.c:devm_extcon_dev_free",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587051904,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586935696,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:422",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_release_resource",
        "kernel/iomem.c:devm_memunmap",
        "mm/dmapool.c:dmam_pool_destroy",
        "drivers/pinctrl/core.c:devm_pinctrl_unregister",
        "drivers/pinctrl/core.c:devm_pinctrl_put",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_free",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios",
        "drivers/pwm/core.c:devm_pwm_put",
        "drivers/clk/clkdev.c:devm_clk_release_clkdev",
        "drivers/clk/clk.c:devm_clk_hw_unregister",
        "drivers/clk/clk.c:devm_clk_unregister",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free",
        "drivers/regulator/devres.c:devm_regulator_bulk_unregister_supply_alias",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/base/core.c:devm_device_remove_groups",
        "drivers/base/core.c:devm_device_remove_group",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_unregister",
        "drivers/leds/led-class.c:devm_led_classdev_unregister",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_unregister",
        "drivers/extcon/devres.c:devm_extcon_dev_free",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586935696,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587499708,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:415",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_release_action"
      ],
      "caller_func": [
        "kernel/resource.c:devm_release_resource",
        "kernel/iomem.c:devm_memunmap",
        "mm/dmapool.c:dmam_pool_destroy",
        "drivers/pinctrl/core.c:devm_pinctrl_unregister",
        "drivers/pinctrl/core.c:devm_pinctrl_put",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_free",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios",
        "drivers/video/backlight/backlight.c:devm_backlight_device_unregister",
        "drivers/clk/clk-devres.c:devm_clk_put",
        "drivers/clk/clkdev.c:devm_clk_release_clkdev",
        "drivers/clk/clk.c:devm_clk_hw_unregister",
        "drivers/clk/clk.c:devm_clk_unregister",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free",
        "drivers/regulator/devres.c:devm_regulator_unregister_notifier",
        "drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_put",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/base/core.c:devm_device_remove_groups",
        "drivers/base/core.c:devm_device_remove_group",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_del_irq_chip",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_unregister",
        "drivers/leds/led-class.c:devm_led_classdev_unregister",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_unregister",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_unregister",
        "drivers/extcon/devres.c:devm_extcon_dev_free",
        "drivers/nvmem/core.c:devm_nvmem_cell_put",
        "drivers/nvmem/core.c:devm_nvmem_device_put",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587499392,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588823612,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:415",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_release_action"
      ],
      "caller_func": [
        "kernel/resource.c:devm_release_resource",
        "kernel/iomem.c:devm_memunmap",
        "mm/dmapool.c:dmam_pool_destroy",
        "drivers/pinctrl/core.c:devm_pinctrl_unregister",
        "drivers/pinctrl/core.c:devm_pinctrl_put",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_free",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put",
        "drivers/video/backlight/backlight.c:devm_backlight_device_unregister",
        "drivers/clk/clk-devres.c:devm_clk_put",
        "drivers/clk/clkdev.c:devm_clk_release_clkdev",
        "drivers/clk/clk.c:devm_clk_hw_unregister",
        "drivers/clk/clk.c:devm_clk_unregister",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free",
        "drivers/regulator/devres.c:devm_regulator_unregister_notifier",
        "drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_put",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/base/core.c:devm_device_remove_groups",
        "drivers/base/core.c:devm_device_remove_group",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_del_irq_chip",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_unregister",
        "drivers/leds/led-class.c:devm_led_classdev_unregister",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_unregister",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_unregister",
        "drivers/extcon/devres.c:devm_extcon_dev_free",
        "drivers/nvmem/core.c:devm_nvmem_cell_put",
        "drivers/nvmem/core.c:devm_nvmem_device_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588823232,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590323036,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:420",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_release_action"
      ],
      "caller_func": [
        "kernel/resource.c:devm_release_resource",
        "kernel/iomem.c:devm_memunmap",
        "mm/dmapool.c:dmam_pool_destroy",
        "drivers/pinctrl/core.c:devm_pinctrl_unregister",
        "drivers/pinctrl/core.c:devm_pinctrl_put",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put",
        "drivers/video/backlight/backlight.c:devm_backlight_device_unregister",
        "drivers/clk/clk-devres.c:devm_clk_put",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free",
        "drivers/regulator/devres.c:devm_regulator_unregister_notifier",
        "drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_bulk_get_enable",
        "drivers/regulator/devres.c:_devm_regulator_get_enable",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_del_irq_chip",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_unregister",
        "drivers/leds/led-class.c:devm_led_classdev_unregister",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_unregister",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_unregister",
        "drivers/extcon/devres.c:devm_extcon_dev_free",
        "drivers/nvmem/core.c:devm_nvmem_cell_put",
        "drivers/nvmem/core.c:devm_nvmem_device_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590322608,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590642956,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:420",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_release_action"
      ],
      "caller_func": [
        "kernel/resource.c:devm_release_resource",
        "kernel/iomem.c:devm_memunmap",
        "mm/dmapool.c:dmam_pool_destroy",
        "drivers/pinctrl/core.c:devm_pinctrl_unregister",
        "drivers/pinctrl/core.c:devm_pinctrl_put",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put",
        "drivers/video/backlight/backlight.c:devm_backlight_device_unregister",
        "drivers/clk/clk-devres.c:devm_clk_put",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free",
        "drivers/regulator/devres.c:devm_regulator_unregister_notifier",
        "drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_bulk_get_enable",
        "drivers/regulator/devres.c:_devm_regulator_get_enable",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_del_irq_chip",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_unregister",
        "drivers/leds/led-class.c:devm_led_classdev_unregister",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_unregister",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_unregister",
        "drivers/extcon/devres.c:devm_extcon_dev_free",
        "drivers/nvmem/core.c:devm_nvmem_cell_put",
        "drivers/nvmem/core.c:devm_nvmem_device_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590642528,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591003052,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:420",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_release_action"
      ],
      "caller_func": [
        "kernel/resource.c:devm_release_resource",
        "kernel/iomem.c:devm_memunmap",
        "mm/dmapool.c:dmam_pool_destroy",
        "drivers/pinctrl/core.c:devm_pinctrl_unregister",
        "drivers/pinctrl/core.c:devm_pinctrl_put",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put",
        "drivers/video/backlight/backlight.c:devm_backlight_device_unregister",
        "drivers/clk/clk-devres.c:devm_clk_put",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free",
        "drivers/regulator/devres.c:devm_regulator_unregister_notifier",
        "drivers/regulator/devres.c:devm_regulator_bulk_register_supply_alias",
        "drivers/regulator/devres.c:devm_regulator_bulk_get_enable",
        "drivers/regulator/devres.c:_devm_regulator_get_enable",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/base/regmap/regmap-irq.c:devm_regmap_del_irq_chip",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_unregister",
        "drivers/leds/led-class.c:devm_led_classdev_unregister",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_unregister",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_unregister",
        "drivers/extcon/devres.c:devm_extcon_dev_free",
        "drivers/nvmem/core.c:devm_nvmem_cell_put",
        "drivers/nvmem/core.c:devm_nvmem_device_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591002624,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499005592,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:406",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_release_resource",
        "kernel/iomem.c:devm_memunmap",
        "mm/dmapool.c:dmam_pool_destroy",
        "drivers/pinctrl/core.c:devm_pinctrl_unregister",
        "drivers/pinctrl/core.c:devm_pinctrl_put",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_free",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios",
        "drivers/pwm/core.c:devm_pwm_put",
        "drivers/clk/clk.c:devm_clk_hw_unregister",
        "drivers/clk/clk.c:devm_clk_unregister",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/base/core.c:devm_device_remove_groups",
        "drivers/base/core.c:devm_device_remove_group",
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_release_action",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_unregister",
        "drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_unregister",
        "drivers/leds/led-class.c:devm_led_classdev_unregister",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_unregister",
        "drivers/extcon/devres.c:devm_extcon_dev_free",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499005592,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231570596,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:406",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_release_resource",
        "kernel/iomem.c:devm_memunmap",
        "mm/dmapool.c:dmam_pool_destroy",
        "drivers/pinctrl/core.c:devm_pinctrl_unregister",
        "drivers/pinctrl/core.c:devm_pinctrl_put",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_free",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put",
        "drivers/pwm/core.c:devm_pwm_put",
        "drivers/clk/clk.c:devm_clk_hw_unregister",
        "drivers/clk/clk.c:devm_clk_unregister",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/base/core.c:devm_device_remove_groups",
        "drivers/base/core.c:devm_device_remove_group",
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_release_action",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_unregister",
        "drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_unregister",
        "drivers/leds/led-class.c:devm_led_classdev_unregister",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_unregister",
        "drivers/extcon/devres.c:devm_extcon_dev_free",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231570596,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292165360,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:406",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_release_resource",
        "kernel/iomem.c:devm_memunmap",
        "mm/dmapool.c:dmam_pool_destroy",
        "drivers/pinctrl/core.c:devm_pinctrl_unregister",
        "drivers/pinctrl/core.c:devm_pinctrl_put",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_free",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put",
        "drivers/pwm/core.c:devm_pwm_put",
        "drivers/video/backlight/backlight.c:devm_backlight_device_unregister",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/base/core.c:devm_device_remove_groups",
        "drivers/base/core.c:devm_device_remove_group",
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_release_action",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy",
        "drivers/net/phy/mdio_bus.c:devm_mdiobus_free",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_unregister",
        "drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_unregister",
        "drivers/leds/led-class.c:devm_led_classdev_unregister",
        "drivers/of/platform.c:devm_of_platform_depopulate",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_unregister",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_free",
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_unregister",
        "drivers/extcon/devres.c:devm_extcon_dev_free",
        "drivers/nvmem/core.c:devm_nvmem_cell_put",
        "drivers/nvmem/core.c:devm_nvmem_device_put",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292165360,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276376784,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:406",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_release_resource",
        "kernel/iomem.c:devm_memunmap",
        "mm/dmapool.c:dmam_pool_destroy",
        "drivers/pinctrl/core.c:devm_pinctrl_unregister",
        "drivers/pinctrl/core.c:devm_pinctrl_put",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_free",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put",
        "drivers/pwm/core.c:devm_pwm_put",
        "drivers/clk/clk.c:devm_clk_hw_unregister",
        "drivers/clk/clk.c:devm_clk_unregister",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/base/core.c:devm_device_remove_groups",
        "drivers/base/core.c:devm_device_remove_group",
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_release_action",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_unregister",
        "drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_unregister",
        "drivers/leds/led-class.c:devm_led_classdev_unregister",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_unregister",
        "drivers/extcon/devres.c:devm_extcon_dev_free",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276376784,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585964176,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:406",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_release_resource",
        "kernel/iomem.c:devm_memunmap",
        "mm/dmapool.c:dmam_pool_destroy",
        "drivers/pinctrl/core.c:devm_pinctrl_unregister",
        "drivers/pinctrl/core.c:devm_pinctrl_put",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_free",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios",
        "drivers/pwm/core.c:devm_pwm_put",
        "drivers/clk/clk.c:devm_clk_hw_unregister",
        "drivers/clk/clk.c:devm_clk_unregister",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/base/core.c:devm_device_remove_groups",
        "drivers/base/core.c:devm_device_remove_group",
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_release_action",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_unregister",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_unregister",
        "drivers/extcon/devres.c:devm_extcon_dev_free",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585964176,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585813440,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:406",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_release_resource",
        "kernel/iomem.c:devm_memunmap",
        "mm/dmapool.c:dmam_pool_destroy",
        "drivers/pinctrl/core.c:devm_pinctrl_unregister",
        "drivers/pinctrl/core.c:devm_pinctrl_put",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_free",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios",
        "drivers/clk/clk.c:devm_clk_hw_unregister",
        "drivers/clk/clk.c:devm_clk_unregister",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/base/core.c:devm_device_remove_groups",
        "drivers/base/core.c:devm_device_remove_group",
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_release_action",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_unregister",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585813440,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586153984,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:406",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_release_resource",
        "kernel/iomem.c:devm_memunmap",
        "mm/dmapool.c:dmam_pool_destroy",
        "drivers/pinctrl/core.c:devm_pinctrl_unregister",
        "drivers/pinctrl/core.c:devm_pinctrl_put",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_free",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios",
        "drivers/pwm/core.c:devm_pwm_put",
        "drivers/clk/clk.c:devm_clk_hw_unregister",
        "drivers/clk/clk.c:devm_clk_unregister",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/base/core.c:devm_device_remove_groups",
        "drivers/base/core.c:devm_device_remove_group",
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_release_action",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_unregister",
        "drivers/leds/led-class.c:devm_led_classdev_unregister",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_unregister",
        "drivers/extcon/devres.c:devm_extcon_dev_free",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586153984,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int devres_release(struct device * dev, dr_release_t release, dr_match_t match, void * match_data)
```

```json
{
  "name": "devres_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586262688,
      "name": "devres_release",
      "external": true,
      "loc": "drivers/base/devres.c:406",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_release_resource",
        "kernel/iomem.c:devm_memunmap",
        "mm/dmapool.c:dmam_pool_destroy",
        "drivers/pinctrl/core.c:devm_pinctrl_unregister",
        "drivers/pinctrl/core.c:devm_pinctrl_put",
        "drivers/gpio/gpiolib-devres.c:devm_gpio_free",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put_array",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_put",
        "drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_remove_driver_gpios",
        "drivers/pwm/core.c:devm_pwm_put",
        "drivers/clk/clk.c:devm_clk_hw_unregister",
        "drivers/clk/clk.c:devm_clk_unregister",
        "drivers/dma/acpi-dma.c:devm_acpi_dma_controller_free",
        "drivers/char/hw_random/core.c:devm_hwrng_unregister",
        "drivers/base/core.c:devm_device_remove_groups",
        "drivers/base/core.c:devm_device_remove_group",
        "drivers/base/devres.c:devm_free_pages",
        "drivers/base/devres.c:devm_release_action",
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_destroy",
        "drivers/hwmon/hwmon.c:devm_hwmon_device_unregister",
        "drivers/leds/led-class.c:devm_led_classdev_unregister",
        "drivers/mailbox/mailbox.c:devm_mbox_controller_unregister",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_unregister_opp_notifier",
        "drivers/devfreq/devfreq.c:devm_devfreq_remove_device",
        "drivers/devfreq/devfreq-event.c:devm_devfreq_event_remove_edev",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier_all",
        "drivers/extcon/devres.c:devm_extcon_unregister_notifier",
        "drivers/extcon/devres.c:devm_extcon_dev_unregister",
        "drivers/extcon/devres.c:devm_extcon_dev_free",
        "drivers/nvmem/core.c:devm_nvmem_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586262688,
      "name": "devres_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
