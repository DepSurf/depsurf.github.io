# Function: <code>gpio_to_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583190752,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:68",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_request_gpio",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/net/phy/fixed_phy.c:fixed_phy_update_regs",
        "drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy",
        "drivers/i2c/i2c-core.c:set_scl_gpio_value",
        "drivers/i2c/i2c-core.c:get_scl_gpio_value",
        "drivers/i2c/i2c-core.c:get_sda_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd",
        "drivers/clk/clk-gpio.c:clk_register_gpio",
        "drivers/clk/clk-gpio.c:clk_register_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583190752,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583493424,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:85",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_request_gpio",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/i2c/i2c-core.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core.c:set_scl_gpio_value",
        "drivers/i2c/i2c-core.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_ro",
        "drivers/clk/clk-gpio.c:clk_register_gpio",
        "drivers/clk/clk-gpio.c:clk_register_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583493424,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583632640,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:88",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_request_gpio",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/clk/clk-gpio.c:clk_register_gpio",
        "drivers/clk/clk-gpio.c:clk_register_gpio",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/i2c/i2c-core.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core.c:set_scl_gpio_value",
        "drivers/i2c/i2c-core.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583632640,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583672016,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:89",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_request_gpio",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/clk/clk-gpio.c:clk_register_gpio",
        "drivers/clk/clk-gpio.c:clk_register_gpio",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672016,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583926752,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:97",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583926752,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584120624,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:105",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584120624,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584205088,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:106",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/regulator/core.c:regulator_register",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584205088,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584394240,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:106",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584394240,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584529136,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:108",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584529136,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585188496,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:108",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_ready_for_gpio_range",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585188496,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:105",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_ready_for_gpio_range",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591385573,
      "name": "gpio_to_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585347488,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:107",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591328003,
      "name": "gpio_to_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585232016,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:107",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592350671,
      "name": "gpio_to_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585687312,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:107",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594212255,
      "name": "gpio_to_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586854192,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587998288,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:108",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587998288,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588272976,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:125",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/pinctrl/core.c:pinctrl_gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588272976,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588565248,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:113",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_pins_show",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588565248,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496711512,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:108",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496711512,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230004380,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:108",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-mvebu/pm-board.c:mvebu_armada_pm_init",
        "arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3517_legacy_init",
        "arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3517_legacy_init",
        "arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3517_legacy_init",
        "arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3x_usb_hub_init",
        "arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3x_usb_hub_init",
        "drivers/pinctrl/core.c:pinctrl_gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/tty/serial/omap-serial.c:serial_omap_probe",
        "drivers/tty/serial/omap-serial.c:serial_omap_config_rs485",
        "drivers/tty/serial/omap-serial.c:serial_omap_start_tx",
        "drivers/tty/serial/omap-serial.c:serial_omap_start_tx",
        "drivers/tty/serial/omap-serial.c:serial_omap_stop_tx",
        "drivers/tty/serial/omap-serial.c:serial_omap_stop_tx",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy",
        "sound/soc/soc-jack.c:snd_soc_jack_add_gpios",
        "sound/soc/soc-ac97.c:snd_soc_ac97_reset",
        "sound/soc/soc-ac97.c:snd_soc_ac97_reset",
        "sound/soc/soc-ac97.c:snd_soc_ac97_reset",
        "sound/soc/soc-ac97.c:snd_soc_ac97_reset",
        "sound/soc/soc-ac97.c:snd_soc_ac97_warm_reset",
        "sound/soc/soc-ac97.c:snd_soc_ac97_warm_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230004380,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290800992,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:108",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290800992,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275473790,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:108",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275473790,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584486064,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:108",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584486064,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584424192,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:108",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584424192,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584480800,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:108",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584480800,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct gpio_desc * gpio_to_desc(unsigned int gpio)
```

```json
{
  "name": "gpio_to_desc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584586896,
      "name": "gpio_to_desc",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:108",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/core.c:pinctrl_gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584586896,
      "name": "gpio_to_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
