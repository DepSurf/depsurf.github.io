# Function: <code>acpi_install_address_space_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583644607,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:77",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/i2c/i2c-core.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583644607,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583967694,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:77",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/i2c/i2c-core.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583967694,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584109447,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:77",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/i2c/i2c-core.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584109447,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584176473,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:77",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584176473,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584482161,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:77",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584482161,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584706600,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:43",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584706600,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584806700,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:43",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584806700,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585009592,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:43",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585009592,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585145677,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:43",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585145677,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585850849,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:43",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585850849,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585972000,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:43",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585972000,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585849068,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:43",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585849068,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586335915,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:43",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler",
        "drivers/acpi/prmt.c:init_prmt",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586335915,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587582721,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:43",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler",
        "drivers/acpi/prmt.c:init_prmt",
        "drivers/acpi/acpi_pcc.c:acpi_init_pcc",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587582721,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588872208,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:97",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler",
        "drivers/acpi/prmt.c:init_prmt",
        "drivers/acpi/acpi_pcc.c:acpi_init_pcc",
        "drivers/acpi/acpi_ffh.c:acpi_init_ffh",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588872208,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589161648,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:97",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_attach_handler",
        "drivers/acpi/prmt.c:init_prmt",
        "drivers/acpi/acpi_pcc.c:acpi_init_pcc",
        "drivers/acpi/acpi_ffh.c:acpi_init_ffh",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589161648,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589468016,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:97",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_attach_handler",
        "drivers/acpi/prmt.c:init_prmt",
        "drivers/acpi/acpi_pcc.c:acpi_init_pcc",
        "drivers/acpi/acpi_ffh.c:acpi_init_ffh",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589468016,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497509244,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:43",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497509244,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585044473,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:43",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585044473,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584960028,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:43",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584960028,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585097261,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:43",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585097261,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```

```json
{
  "name": "acpi_install_address_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585203421,
      "name": "acpi_install_address_space_handler",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfregn.c:43",
      "file": "drivers/acpi/acpica/evxfregn.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585203421,
      "name": "acpi_install_address_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void * context)
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
