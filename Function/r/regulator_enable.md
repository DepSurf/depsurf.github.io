# Function: <code>regulator_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583934736,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2135",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/phy/phy-generic.c:usb_gen_phy_init",
        "drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread",
        "drivers/power/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583934736,
      "name": "regulator_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584269552,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2187",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/power/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584269552,
      "name": "regulator_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584451408,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2188",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584451408,
      "name": "regulator_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584535664,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2200",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584535664,
      "name": "regulator_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584945904,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2200",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584945904,
      "name": "regulator_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2257",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585188481,
      "name": "regulator_enable.cold.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071585175792,
      "name": "regulator_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585296880,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2581",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585296880,
      "name": "regulator_enable",
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
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585507488,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2536",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585507488,
      "name": "regulator_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585649824,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2544",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585649824,
      "name": "regulator_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586377516,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2575",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:set_machine_constraints"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:wm5102_clear_write_sequencer",
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/opp/core.c:_generic_set_opp_regulator",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586375872,
      "name": "regulator_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586495388,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2700",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:set_machine_constraints"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:wm5102_clear_write_sequencer",
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/opp/core.c:_generic_set_opp_regulator",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586493584,
      "name": "regulator_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586378428,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2701",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:set_machine_constraints"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/opp/core.c:_set_opp",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586376608,
      "name": "regulator_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586901884,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2801",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:set_machine_constraints"
      ],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/opp/core.c:_set_opp",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586899936,
      "name": "regulator_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588190668,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2848",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints"
      ],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_power_on",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588190272,
      "name": "regulator_enable",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589592433,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2880",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints"
      ],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_power_on",
        "drivers/regulator/devres.c:devm_regulator_bulk_get_enable",
        "drivers/regulator/devres.c:_devm_regulator_get_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/opp/core.c:_opp_config_regulator_single",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589592032,
      "name": "regulator_enable",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589894465,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2946",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints"
      ],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_power_on",
        "drivers/regulator/devres.c:devm_regulator_bulk_get_enable",
        "drivers/regulator/devres.c:_devm_regulator_get_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/opp/core.c:_opp_config_regulator_single",
        "drivers/mmc/core/regulator.c:mmc_regulator_enable_vqmmc",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589894064,
      "name": "regulator_enable",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590232209,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2949",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints"
      ],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_power_on",
        "drivers/regulator/devres.c:devm_regulator_bulk_get_enable",
        "drivers/regulator/devres.c:_devm_regulator_get_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_resume",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/opp/core.c:_opp_config_regulator_single",
        "drivers/mmc/core/regulator.c:mmc_regulator_enable_vqmmc",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590231808,
      "name": "regulator_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498311376,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2544",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr",
        "drivers/mmc/host/mmci.c:mmci_set_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498311376,
      "name": "regulator_enable",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230992512,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2544",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/soc/imx/gpc.c:imx6_pm_domain_power_on",
        "drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/usb/phy/phy-generic.c:usb_gen_phy_init",
        "drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr",
        "drivers/mmc/host/mmci.c:mmci_set_ios",
        "drivers/mmc/host/sdhci.c:sdhci_setup_host",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_power",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_power",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_disable_supply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230992512,
      "name": "regulator_enable",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291482944,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2544",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291482944,
      "name": "regulator_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276002004,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2544",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276002004,
      "name": "regulator_enable",
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
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585410432,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2544",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585410432,
      "name": "regulator_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585280896,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2544",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585280896,
      "name": "regulator_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585600224,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2544",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585600224,
      "name": "regulator_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "regulator_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585708352,
      "name": "regulator_enable",
      "external": true,
      "loc": "drivers/regulator/core.c:2544",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_start",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585708352,
      "name": "regulator_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
