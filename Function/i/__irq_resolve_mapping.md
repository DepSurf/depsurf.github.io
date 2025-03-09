# Function: <code>__irq_resolve_mapping</code>

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
struct irq_desc * __irq_resolve_mapping(struct irq_domain * domain, irq_hw_number_t hwirq, unsigned int * irq)
```

```json
{
  "name": "__irq_resolve_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580180192,
      "name": "__irq_resolve_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:895",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "kernel/irq/irqdesc.c:generic_handle_domain_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
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
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180192,
      "name": "__irq_resolve_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
struct irq_desc * __irq_resolve_mapping(struct irq_domain * domain, irq_hw_number_t hwirq, unsigned int * irq)
```

```json
{
  "name": "__irq_resolve_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580328224,
      "name": "__irq_resolve_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:895",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "kernel/irq/irqdesc.c:generic_handle_domain_nmi",
        "kernel/irq/irqdesc.c:generic_handle_domain_irq",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity",
        "kernel/irq/irq_sim.c:irq_sim_handle_irq",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
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
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328224,
      "name": "__irq_resolve_mapping",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct irq_desc * __irq_resolve_mapping(struct irq_domain * domain, irq_hw_number_t hwirq, unsigned int * irq)
```

```json
{
  "name": "__irq_resolve_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580543920,
      "name": "__irq_resolve_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:952",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "kernel/irq/irqdesc.c:generic_handle_domain_nmi",
        "kernel/irq/irqdesc.c:generic_handle_domain_irq_safe",
        "kernel/irq/irqdesc.c:generic_handle_domain_irq",
        "kernel/irq/generic-chip.c:irq_gc_get_irq_data",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity",
        "kernel/irq/irq_sim.c:irq_sim_handle_irq",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
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
      "addr": 18446744071580543920,
      "name": "__irq_resolve_mapping",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct irq_desc * __irq_resolve_mapping(struct irq_domain * domain, irq_hw_number_t hwirq, unsigned int * irq)
```

```json
{
  "name": "__irq_resolve_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580617376,
      "name": "__irq_resolve_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:933",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "kernel/irq/irqdesc.c:generic_handle_domain_nmi",
        "kernel/irq/irqdesc.c:generic_handle_domain_irq_safe",
        "kernel/irq/irqdesc.c:generic_handle_domain_irq",
        "kernel/irq/generic-chip.c:irq_gc_get_irq_data",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity",
        "kernel/irq/irq_sim.c:irq_sim_handle_irq",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
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
      "addr": 18446744071580617376,
      "name": "__irq_resolve_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct irq_desc * __irq_resolve_mapping(struct irq_domain * domain, irq_hw_number_t hwirq, unsigned int * irq)
```

```json
{
  "name": "__irq_resolve_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580682272,
      "name": "__irq_resolve_mapping",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:933",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "kernel/irq/irqdesc.c:generic_handle_domain_nmi",
        "kernel/irq/irqdesc.c:generic_handle_domain_irq_safe",
        "kernel/irq/irqdesc.c:generic_handle_domain_irq",
        "kernel/irq/generic-chip.c:irq_gc_get_irq_data",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity",
        "kernel/irq/irq_sim.c:irq_sim_handle_irq",
        "kernel/irq/msi.c:msi_domain_alloc",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
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
      "addr": 18446744071580682272,
      "name": "__irq_resolve_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct irq_desc * __irq_resolve_mapping(struct irq_domain * domain, irq_hw_number_t hwirq, unsigned int * irq)
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
