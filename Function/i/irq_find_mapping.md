# Function: <code>irq_find_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579764560,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:654",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/htirq.c:htirq_domain_alloc",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpio-intel-mid.c:intel_mid_irq_handler",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/gpio/gpio-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpio-zx.c:zx_irq_handler",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579764560,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579787680,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:697",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/htirq.c:htirq_domain_alloc",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/gpio/gpio-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpio-zx.c:zx_irq_handler",
        "drivers/pci/host/pcie-designware.c:dw_handle_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787680,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579814800,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:720",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/htirq.c:htirq_domain_alloc",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/host/pcie-designware.c:dw_handle_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/i2c/i2c-core.c:i2c_handle_smbus_host_notify",
        "drivers/i2c/i2c-core.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814800,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579813168,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:858",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/htirq.c:htirq_domain_alloc",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579813168,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579846320,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:872",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579846320,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880128,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:874",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880128,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579927408,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:874",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579927408,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579965824,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:891",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965824,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580015600,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:893",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015600,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580068464,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:878",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580068464,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580051056,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:902",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580051056,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580051088,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:869",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580051088,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579372426,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:420",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580175565,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:420",
      "file": "kernel/irq/generic-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580187193,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:420",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580195014,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:420",
      "file": "kernel/irq/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:msi_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585655021,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:420",
      "file": "drivers/pinctrl/pinctrl-sx150x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585679594,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:420",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585695439,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:420",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585736227,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:420",
      "file": "drivers/gpio/gpio-crystalcove.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587665399,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:420",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587734392,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:420",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587753106,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:420",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587771864,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:420",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587782804,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:420",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587786605,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:420",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587790453,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:420",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589127243,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:420",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579434485,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:434",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580323719,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:434",
      "file": "kernel/irq/generic-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580335807,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:434",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580336850,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:434",
      "file": "kernel/irq/irq_sim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irq_sim.c:irq_sim_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580345854,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:434",
      "file": "kernel/irq/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:msi_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586819584,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:434",
      "file": "drivers/pinctrl/pinctrl-sx150x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586844697,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:434",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586862516,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:434",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586918571,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:434",
      "file": "drivers/gpio/gpio-crystalcove.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589012197,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:434",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589079827,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:434",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589097866,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:434",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589118116,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:434",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589129849,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:434",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589133976,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:434",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589138149,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:434",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590575855,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:434",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579520437,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:422",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580538887,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:422",
      "file": "kernel/irq/generic-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:irq_gc_get_irq_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580551011,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:422",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580553818,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:422",
      "file": "kernel/irq/irq_sim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irq_sim.c:irq_sim_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580564462,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:422",
      "file": "kernel/irq/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:msi_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587957688,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:422",
      "file": "drivers/pinctrl/pinctrl-sx150x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587983674,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:422",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588008345,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:422",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588073675,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:422",
      "file": "drivers/gpio/gpio-crystalcove.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590540165,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:422",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590612291,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:422",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590633190,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:422",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590657540,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:422",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590673481,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:422",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590678124,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:422",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590683386,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:422",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592232079,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:422",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579532949,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580612279,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "kernel/irq/generic-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:irq_gc_get_irq_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580624340,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580627050,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "kernel/irq/irq_sim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irq_sim.c:irq_sim_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580638190,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "kernel/irq/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:msi_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588232120,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/pinctrl/pinctrl-sx150x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588283495,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588348203,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/gpio/gpio-crystalcove.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590865984,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590953388,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590974326,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590998452,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591014423,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591019208,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591024489,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592657151,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579561717,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580676583,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "kernel/irq/generic-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:irq_gc_get_irq_data",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580689348,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580692106,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "kernel/irq/irq_sim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irq_sim.c:irq_sim_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580703342,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "kernel/irq/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:msi_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588525032,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/pinctrl/pinctrl-sx150x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588576535,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588642811,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/gpio/gpio-crystalcove.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591209488,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591297196,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591318294,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591342468,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591358423,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591363256,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591368537,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593402303,
      "name": "irq_find_mapping",
      "external": false,
      "loc": "include/linux/irqdomain.h:425",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491217320,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:893",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:handle_domain_nmi",
        "kernel/irq/irqdesc.c:handle_domain_nmi",
        "kernel/irq/irqdesc.c:__handle_domain_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/irqchip/irq-al-fic.c:al_fic_irq_handler",
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler",
        "drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_handle_irq",
        "drivers/irqchip/irq-gic.c:gic_handle_cascade_irq",
        "drivers/irqchip/irq-partition-percpu.c:partition_handle_irq",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler",
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_irq_handle",
        "drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_suspend",
        "drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_handle_cascade_irq",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_handle_cascade_irq",
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_irq_handler",
        "drivers/irqchip/qcom-irq-combiner.c:combiner_handle_irq",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler",
        "drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_handle",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pctl_pin_dbg_show",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_handler",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_3700_pinctrl_resume",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_handler",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_gpio_to_irq",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_find_irq",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_debounce",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpio-davinci.c:gpio_irq_handler",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_to_irq",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler",
        "drivers/gpio/gpio-pl061.c:pl061_irq_handler",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_unmap_msi",
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs",
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irq",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_handle_msi_irq",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_leg_handler",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_isr",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_handler",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_isr",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/acpi/irq.c:acpi_unregister_gsi",
        "drivers/acpi/irq.c:acpi_gsi_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_thread",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491217320,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225232624,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:893",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:handle_domain_nmi",
        "kernel/irq/irqdesc.c:__handle_domain_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/irqchip/irq-al-fic.c:al_fic_irq_handler",
        "drivers/irqchip/exynos-combiner.c:combiner_handle_cascade_irq",
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler",
        "drivers/irqchip/irq-orion.c:orion_bridge_irq_handler",
        "drivers/irqchip/irq-gic.c:gic_handle_cascade_irq",
        "drivers/irqchip/irq-partition-percpu.c:partition_handle_irq",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_handle_cascade_irq",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_handle_msi_irq",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler",
        "drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_suspend",
        "drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_irq_handler",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_handle",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_gpio_request_free",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_demux_eint16_31",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_find_irq",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_debounce",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_to_irq",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler",
        "drivers/gpio/gpio-omap.c:omap_gpio_irq_handler",
        "drivers/gpio/gpio-pl061.c:pl061_irq_handler",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_irq_handler",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_to_irq",
        "drivers/gpio/gpio-vf610.c:vf610_gpio_irq_handler",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_msi_teardown",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_msi_irq",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_unmap_msi",
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs",
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irq",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_isr",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_msi_irq_handler",
        "drivers/soc/dove/pmu.c:pmu_irq_handler",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/tps65217.c:tps65217_remove",
        "drivers/mfd/tps65217.c:tps65217_irq_thread",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_thread",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify",
        "drivers/memory/omap-gpmc.c:gpmc_remove",
        "drivers/memory/omap-gpmc.c:gpmc_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225232624,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284122096,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:893",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/sysdev/xics/icp-native.c:icp_native_get_irq",
        "arch/powerpc/sysdev/xics/icp-hv.c:icp_hv_get_irq",
        "arch/powerpc/sysdev/xics/icp-opal.c:icp_opal_get_irq",
        "arch/powerpc/platforms/powernv/opal-irqchip.c:opal_handle_events",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "drivers/irqchip/irq-al-fic.c:al_fic_irq_handler",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_handle",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_thread",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284122096,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271754650,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:893",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_gc_get_irq_data",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/irqchip/irq-al-fic.c:al_fic_irq_handler",
        "drivers/irqchip/irq-sifive-plic.c:plic_handle_irq",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-single.c:pcs_irq_handle",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_thread",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271754650,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579984336,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:893",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984336,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579922112,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:893",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579922112,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579975872,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:893",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975872,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
```

```json
{
  "name": "irq_find_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580022496,
      "name": "irq_find_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:893",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022496,
      "name": "irq_find_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
unsigned int irq_find_mapping(struct irq_domain * domain, irq_hw_number_t hwirq)
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
