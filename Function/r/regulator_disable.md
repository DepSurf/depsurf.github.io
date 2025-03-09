# Function: <code>regulator_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583931920,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2252",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_power_off",
        "drivers/regulator/core.c:regulator_disable",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread",
        "drivers/power/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583931920,
      "name": "regulator_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584269440,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2301",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_power_off",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/power/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584269440,
      "name": "regulator_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584451296,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2302",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_power_off",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584451296,
      "name": "regulator_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584535568,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2314",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584535568,
      "name": "regulator_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584945808,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2314",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584945808,
      "name": "regulator_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585175680,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2371",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/regulator/core.c:regulator_force_disable",
        "drivers/regulator/core.c:regulator_disable",
        "drivers/regulator/core.c:regulator_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585175680,
      "name": "regulator_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585295392,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2691",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/core.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585295392,
      "name": "regulator_disable",
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585505920,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2646",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585505920,
      "name": "regulator_disable",
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585648576,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2654",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585648576,
      "name": "regulator_disable",
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586374602,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2685",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred"
      ],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:wm5102_clear_write_sequencer",
        "drivers/usb/dwc2/platform.c:dwc2_suspend",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586374416,
      "name": "regulator_disable",
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586492374,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2810",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred"
      ],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:wm5102_clear_write_sequencer",
        "drivers/usb/dwc2/platform.c:dwc2_suspend",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586492192,
      "name": "regulator_disable",
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586375338,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2808",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred"
      ],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/platform.c:dwc2_suspend",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:_set_opp",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586375152,
      "name": "regulator_disable",
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586898570,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2908",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred"
      ],
      "caller_func": [
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_suspend",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:_set_opp",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586898384,
      "name": "regulator_disable",
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588188774,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2955",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred"
      ],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_power_off",
        "drivers/phy/phy-core.c:phy_power_on",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_suspend",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/opp/core.c:dev_pm_opp_put_regulators",
        "drivers/opp/core.c:_set_opp",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588188560,
      "name": "regulator_disable",
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589590438,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2987",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred"
      ],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_power_off",
        "drivers/phy/phy-core.c:phy_power_on",
        "drivers/regulator/devres.c:devm_regulator_bulk_get_enable",
        "drivers/regulator/devres.c:devm_regulator_bulk_disable",
        "drivers/regulator/devres.c:_devm_regulator_get_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_suspend",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/opp/core.c:_opp_clear_config",
        "drivers/opp/core.c:_set_opp",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589590208,
      "name": "regulator_disable",
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589892470,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:3053",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred"
      ],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_power_off",
        "drivers/phy/phy-core.c:phy_power_on",
        "drivers/regulator/devres.c:devm_regulator_bulk_get_enable",
        "drivers/regulator/devres.c:devm_regulator_bulk_disable",
        "drivers/regulator/devres.c:_devm_regulator_get_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_suspend",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/opp/core.c:_opp_clear_config",
        "drivers/opp/core.c:_set_opp",
        "drivers/mmc/core/regulator.c:mmc_regulator_disable_vqmmc",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589892240,
      "name": "regulator_disable",
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590230102,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:3059",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred"
      ],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_power_off",
        "drivers/phy/phy-core.c:phy_power_on",
        "drivers/regulator/devres.c:devm_regulator_bulk_get_enable",
        "drivers/regulator/devres.c:devm_regulator_bulk_disable",
        "drivers/regulator/devres.c:_devm_regulator_get_enable",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/dwc2/platform.c:dwc2_suspend",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/platform.c:dwc2_driver_remove",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/opp/core.c:_opp_clear_config",
        "drivers/opp/core.c:_set_opp",
        "drivers/mmc/core/regulator.c:mmc_regulator_disable_vqmmc",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590229872,
      "name": "regulator_disable",
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498310000,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2654",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_free",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/stmpe.c:stmpe_remove",
        "drivers/mfd/stmpe.c:stmpe_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/ata/libahci_platform.c:ahci_platform_disable_regulators",
        "drivers/ata/libahci_platform.c:ahci_platform_disable_regulators",
        "drivers/ata/libahci_platform.c:ahci_platform_disable_regulators",
        "drivers/net/ethernet/freescale/fec_main.c:fec_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_suspend",
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr",
        "drivers/mmc/host/mmci.c:mmci_set_ios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498310000,
      "name": "regulator_disable",
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230991132,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2654",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset",
        "drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_assert_core_reset",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe",
        "drivers/soc/imx/gpc.c:imx6_pm_domain_power_off",
        "drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on",
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/stmpe.c:stmpe_remove",
        "drivers/mfd/stmpe.c:stmpe_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/ata/libahci_platform.c:ahci_platform_disable_regulators",
        "drivers/ata/libahci_platform.c:ahci_platform_disable_regulators",
        "drivers/ata/libahci_platform.c:ahci_platform_disable_regulators",
        "drivers/net/ethernet/freescale/fec_main.c:fec_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_suspend",
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_remove",
        "drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr",
        "drivers/mmc/host/mmci.c:mmci_set_ios",
        "drivers/mmc/host/sdhci.c:sdhci_remove_host",
        "drivers/mmc/host/sdhci.c:sdhci_cleanup_host",
        "drivers/mmc/host/sdhci.c:sdhci_setup_host",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_power",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_disable_supply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230991132,
      "name": "regulator_disable",
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291481152,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2654",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/stmpe.c:stmpe_remove",
        "drivers/mfd/stmpe.c:stmpe_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291481152,
      "name": "regulator_disable",
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276000864,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2654",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/stmpe.c:stmpe_remove",
        "drivers/mfd/stmpe.c:stmpe_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276000864,
      "name": "regulator_disable",
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585409184,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2654",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585409184,
      "name": "regulator_disable",
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585279648,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2654",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585279648,
      "name": "regulator_disable",
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585598976,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2654",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585598976,
      "name": "regulator_disable",
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
int regulator_disable(struct regulator * regulator)
```

```json
{
  "name": "regulator_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585707104,
      "name": "regulator_disable",
      "external": true,
      "loc": "drivers/regulator/core.c:2654",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_unregister",
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on",
        "drivers/power/supply/charger-manager.c:try_charger_enable",
        "drivers/mmc/core/regulator.c:mmc_regulator_set_ocr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585707104,
      "name": "regulator_disable",
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
