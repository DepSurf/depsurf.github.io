# Function: <code>irq_set_chip_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579752736,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:148",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:arch_setup_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/tps65912-irq.c:tps65912_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752736,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579775280,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:148",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:arch_setup_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579775280,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802128,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:147",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:arch_setup_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802128,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579799296,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:147",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:arch_setup_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579799296,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579833184,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:147",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:arch_setup_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579833184,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579867040,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:145",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:arch_setup_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867040,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579914064,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:145",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:arch_setup_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914064,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579951664,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:145",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:arch_setup_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951664,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580001520,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:145",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:arch_setup_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580001520,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050800,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:145",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpio-msic.c:platform_msic_gpio_probe",
        "drivers/pci/msi.c:arch_setup_msi_irq",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050800,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580033456,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:145",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpio-msic.c:platform_msic_gpio_probe",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580033456,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580034352,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:145",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034352,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580166880,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:145",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580166880,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580313456,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:142",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irq_sim.c:irq_sim_domain_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580313456,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580527120,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:142",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irq_sim.c:irq_sim_domain_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580527120,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580600176,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:142",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irq_sim.c:irq_sim_domain_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580600176,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580664688,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:142",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irq_sim.c:irq_sim_domain_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/xen/events/events_base.c:xen_irq_init",
        "drivers/xen/events/events_base.c:delayed_free_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580664688,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491195200,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:145",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_map",
        "drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_irq_map",
        "drivers/irqchip/qcom-irq-combiner.c:combiner_irq_map",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpio-davinci.c:davinci_gpio_irq_map",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_irq_map",
        "drivers/pci/msi.c:arch_setup_msi_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_map",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_irq_map",
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_map",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intx_map",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_map",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_legacy_map",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_intx_map",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intx_map",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_intx_map",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_init_legacy_irq_map",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_detach_irq",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/stmpe.c:stmpe_irq_unmap",
        "drivers/mfd/stmpe.c:stmpe_irq_map",
        "drivers/mfd/tc3589x.c:tc3589x_irq_unmap",
        "drivers/mfd/tc3589x.c:tc3589x_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_unmap",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_map",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/edac/altera_edac.c:a10_eccmgr_irqdomain_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491195200,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225215772,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:145",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "drivers/irqchip/exynos-combiner.c:combiner_irq_domain_map",
        "drivers/irqchip/irq-hip04.c:hip04_irq_domain_map",
        "drivers/irqchip/irq-rda-intc.c:rda_irq_map",
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_domain_map",
        "drivers/irqchip/irq-aspeed-vic.c:avic_map",
        "drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_map_irq_domain",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_irq_map",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpio-htc-egpio.c:egpio_probe",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_irq_map",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_probe",
        "drivers/pci/msi.c:arch_setup_msi_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_map",
        "drivers/pci/controller/pci-tegra.c:tegra_msi_map",
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_map",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intx_map",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_map",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_intx_map",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intx_map",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_intx_map",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_intx_map",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_detach_irq",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/asic3.c:asic3_irq_remove",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/stmpe.c:stmpe_irq_unmap",
        "drivers/mfd/stmpe.c:stmpe_irq_map",
        "drivers/mfd/tc3589x.c:tc3589x_irq_unmap",
        "drivers/mfd/tc3589x.c:tc3589x_irq_map",
        "drivers/mfd/t7l66xb.c:t7l66xb_probe",
        "drivers/mfd/t7l66xb.c:t7l66xb_detach_irq",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/mfd/tc6393xb.c:tc6393xb_detach_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/tps65217.c:tps65217_irq_map",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_unmap",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_map",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init",
        "drivers/memory/omap-gpmc.c:gpmc_irq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225215772,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284098064,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:145",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/sysdev/mpic.c:mpic_host_map",
        "arch/powerpc/sysdev/mpic.c:mpic_host_map",
        "arch/powerpc/sysdev/mpic.c:mpic_host_map",
        "arch/powerpc/sysdev/xics/ics-rtas.c:ics_rtas_map",
        "arch/powerpc/sysdev/xics/ics-opal.c:ics_opal_map",
        "arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_map",
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irqdomain.c:irq_domain_set_info",
        "drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:arch_setup_msi_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_map",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intx_map",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/stmpe.c:stmpe_irq_unmap",
        "drivers/mfd/stmpe.c:stmpe_irq_map",
        "drivers/mfd/tc3589x.c:tc3589x_irq_unmap",
        "drivers/mfd/tc3589x.c:tc3589x_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_unmap",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_map",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284098064,
      "name": "irq_set_chip_data",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271738778,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:145",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "drivers/irqchip/irq-sifive-plic.c:plic_irqdomain_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:arch_setup_msi_irq",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_map",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intx_map",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_map",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/stmpe.c:stmpe_irq_unmap",
        "drivers/mfd/stmpe.c:stmpe_irq_map",
        "drivers/mfd/tc3589x.c:tc3589x_irq_unmap",
        "drivers/mfd/tc3589x.c:tc3589x_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_unmap",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_map",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271738778,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579970256,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:145",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:arch_setup_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970256,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908080,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:145",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "kernel/irq/irq_sim.c:irq_sim_init",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:arch_setup_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908080,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579961792,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:145",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:arch_setup_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579961792,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int irq_set_chip_data(unsigned int irq, void * data)
```

```json
{
  "name": "irq_set_chip_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008256,
      "name": "irq_set_chip_data",
      "external": true,
      "loc": "kernel/irq/chip.c:145",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_remove_generic_chip",
        "kernel/irq/generic-chip.c:irq_setup_generic_chip",
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/pci/msi.c:arch_setup_msi_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map",
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/arizona-irq.c:arizona_irq_map",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/ezx-pcap.c:ezx_pcap_probe",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map",
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map",
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map",
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map",
        "drivers/mfd/tps6586x.c:tps6586x_irq_map",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008256,
      "name": "irq_set_chip_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
