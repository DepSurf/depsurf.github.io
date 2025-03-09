# Function: <code>i2c_register_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585634160,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:1868",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-sx150x.c:sx150x_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/wm8400-core.c:wm8400_module_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65217.c:tps65217_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_init",
        "drivers/mfd/tps80031.c:tps80031_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/axp20x.c:axp20x_i2c_driver_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77693.c:max77693_i2c_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/ab3100-core.c:ab3100_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/sec-core.c:sec_pmic_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585634160,
      "name": "i2c_register_driver",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586033376,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2065",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-sx150x.c:sx150x_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/wm8400-core.c:wm8400_module_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/tps80031.c:tps80031_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/ab3100-core.c:ab3100_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/sec-core.c:sec_pmic_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586033376,
      "name": "i2c_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586230816,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2350",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/wm8400-core.c:wm8400_module_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/tps80031.c:tps80031_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/ab3100-core.c:ab3100_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/sec-core.c:sec_pmic_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586230816,
      "name": "i2c_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586316928,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1592",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/wm8400-core.c:wm8400_module_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/tps80031.c:tps80031_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/ab3100-core.c:ab3100_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/sec-core.c:sec_pmic_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586316928,
      "name": "i2c_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586780592,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1616",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/wm8400-core.c:wm8400_module_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/tps68470.c:tps68470_driver_init",
        "drivers/mfd/tps80031.c:tps80031_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/ab3100-core.c:ab3100_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/sec-core.c:sec_pmic_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586780592,
      "name": "i2c_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587053584,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1595",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/mfd/wm8400-core.c:wm8400_module_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/tps68470.c:tps68470_driver_init",
        "drivers/mfd/tps80031.c:tps80031_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/ab3100-core.c:ab3100_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/sec-core.c:sec_pmic_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init",
        "drivers/i2c/i2c-core-base.c:i2c_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587053584,
      "name": "i2c_register_driver",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587213648,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1600",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/mfd/wm8400-core.c:wm8400_module_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/tps68470.c:tps68470_driver_init",
        "drivers/mfd/tps80031.c:tps80031_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/ab3100-core.c:ab3100_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/sec-core.c:sec_pmic_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init",
        "drivers/i2c/i2c-core-base.c:i2c_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587213648,
      "name": "i2c_register_driver",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587479038,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1690",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/mfd/wm8400-core.c:wm8400_driver_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/tps68470.c:tps68470_driver_init",
        "drivers/mfd/tps80031.c:tps80031_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/ab3100-core.c:ab3100_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/sec-core.c:sec_pmic_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init",
        "drivers/i2c/i2c-core-base.c:i2c_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587486191,
      "name": "i2c_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587478960,
      "name": "i2c_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587682112,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1695",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/mfd/wm8400-core.c:wm8400_driver_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/tps68470.c:tps68470_driver_init",
        "drivers/mfd/tps80031.c:tps80031_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/ab3100-core.c:ab3100_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/sec-core.c:sec_pmic_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init",
        "drivers/i2c/i2c-core-base.c:i2c_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587682112,
      "name": "i2c_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588548304,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1657",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/mfd/wm8400-core.c:wm8400_driver_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/tps68470.c:tps68470_driver_init",
        "drivers/mfd/tps80031.c:tps80031_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/ab3100-core.c:ab3100_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/sec-core.c:sec_pmic_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init",
        "drivers/i2c/i2c-core-base.c:i2c_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588548304,
      "name": "i2c_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588573856,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1787",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/mfd/wm8400-core.c:wm8400_driver_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/tps68470.c:tps68470_driver_init",
        "drivers/mfd/tps80031.c:tps80031_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/ab3100-core.c:ab3100_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/sec-core.c:sec_pmic_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init",
        "drivers/i2c/i2c-core-base.c:i2c_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588573856,
      "name": "i2c_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588457376,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1847",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/mfd/wm8400-core.c:wm8400_driver_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/tps68470.c:tps68470_driver_init",
        "drivers/mfd/tps80031.c:tps80031_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/sec-core.c:sec_pmic_driver_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init",
        "drivers/i2c/i2c-core-base.c:i2c_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588457376,
      "name": "i2c_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1848",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/mfd/wm8400-core.c:wm8400_driver_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/tps80031.c:tps80031_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init",
        "drivers/i2c/i2c-core-base.c:i2c_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592629923,
      "name": "i2c_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589125456,
      "name": "i2c_register_driver",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1851",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/mfd/wm8400-core.c:wm8400_driver_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init",
        "drivers/i2c/i2c-core-base.c:i2c_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594513530,
      "name": "i2c_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590576592,
      "name": "i2c_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1845",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/tty/serial/max310x.c:max310x_uart_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/wm8400-core.c:wm8400_driver_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_driver_init",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init",
        "drivers/i2c/i2c-core-base.c:i2c_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596307989,
      "name": "i2c_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592233056,
      "name": "i2c_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592659009,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1958",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/tty/serial/max310x.c:max310x_uart_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/wm8400-core.c:wm8400_driver_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_driver_init",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init",
        "drivers/i2c/i2c-core-base.c:i2c_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596837421,
      "name": "i2c_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592658912,
      "name": "i2c_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593404177,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1973",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/tty/serial/max310x.c:max310x_uart_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/wm8400-core.c:wm8400_driver_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_driver_init",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init",
        "drivers/i2c/i2c-core-base.c:i2c_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597761471,
      "name": "i2c_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593404080,
      "name": "i2c_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500838280,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1695",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/mfd/stmpe-i2c.c:stmpe_init",
        "drivers/mfd/tc3589x.c:tc3589x_init",
        "drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_init",
        "drivers/mfd/wm8400-core.c:wm8400_driver_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/tps68470.c:tps68470_driver_init",
        "drivers/mfd/tps80031.c:tps80031_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77620.c:max77620_driver_init",
        "drivers/mfd/max77686.c:max77686_i2c_driver_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/ab3100-core.c:ab3100_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/sec-core.c:sec_pmic_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/as3722.c:as3722_i2c_driver_init",
        "drivers/i2c/i2c-core-base.c:i2c_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500838280,
      "name": "i2c_register_driver",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233357820,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1695",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/mfd/stmpe-i2c.c:stmpe_init",
        "drivers/mfd/tc3589x.c:tc3589x_init",
        "drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_init",
        "drivers/mfd/wm8400-core.c:wm8400_driver_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65217.c:tps65217_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/tps80031.c:tps80031_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77620.c:max77620_driver_init",
        "drivers/mfd/max77686.c:max77686_i2c_driver_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/ab3100-core.c:ab3100_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/sec-core.c:sec_pmic_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/as3722.c:as3722_i2c_driver_init",
        "drivers/rtc/rtc-pcf8523.c:pcf8523_driver_init",
        "drivers/i2c/i2c-core-base.c:i2c_init",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233357820,
      "name": "i2c_register_driver",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294303536,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1695",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/char/tpm/tpm_i2c_atmel.c:i2c_atmel_driver_init",
        "drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_driver_init",
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_driver_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/mfd/stmpe-i2c.c:stmpe_init",
        "drivers/mfd/tc3589x.c:tc3589x_init",
        "drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_init",
        "drivers/mfd/wm8400-core.c:wm8400_driver_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/tps80031.c:tps80031_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77620.c:max77620_driver_init",
        "drivers/mfd/max77686.c:max77686_i2c_driver_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/ab3100-core.c:ab3100_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/sec-core.c:sec_pmic_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/as3722.c:as3722_i2c_driver_init",
        "drivers/i2c/i2c-core-base.c:i2c_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294303536,
      "name": "i2c_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277646334,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1695",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/mfd/stmpe-i2c.c:stmpe_init",
        "drivers/mfd/tc3589x.c:tc3589x_init",
        "drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_init",
        "drivers/mfd/wm8400-core.c:wm8400_driver_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/tps80031.c:tps80031_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77620.c:max77620_driver_init",
        "drivers/mfd/max77686.c:max77686_i2c_driver_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/ab3100-core.c:ab3100_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/sec-core.c:sec_pmic_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/as3722.c:as3722_i2c_driver_init",
        "drivers/i2c/i2c-core-base.c:i2c_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277646334,
      "name": "i2c_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587633360,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1695",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/mfd/wm8400-core.c:wm8400_driver_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/tps68470.c:tps68470_driver_init",
        "drivers/mfd/tps80031.c:tps80031_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/ab3100-core.c:ab3100_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/sec-core.c:sec_pmic_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init",
        "drivers/i2c/i2c-core-base.c:i2c_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587633360,
      "name": "i2c_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```

```json
{
  "name": "i2c_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587744480,
      "name": "i2c_register_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1695",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_init",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_init",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_init",
        "drivers/mfd/wm8400-core.c:wm8400_driver_init",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_init",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_init",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_init",
        "drivers/mfd/tps68470.c:tps68470_driver_init",
        "drivers/mfd/tps80031.c:tps80031_init",
        "drivers/mfd/twl-core.c:twl_driver_init",
        "drivers/mfd/twl6040.c:twl6040_driver_init",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_init",
        "drivers/mfd/da903x.c:da903x_init",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_init",
        "drivers/mfd/lp8788.c:lp8788_init",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_init",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_init",
        "drivers/mfd/max14577.c:max14577_i2c_init",
        "drivers/mfd/max77693.c:max77693_i2c_driver_init",
        "drivers/mfd/max77843.c:max77843_i2c_init",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_init",
        "drivers/mfd/max8997.c:max8997_i2c_init",
        "drivers/mfd/max8998.c:max8998_i2c_init",
        "drivers/mfd/ab3100-core.c:ab3100_i2c_init",
        "drivers/mfd/adp5520.c:adp5520_driver_init",
        "drivers/mfd/tps6586x.c:tps6586x_init",
        "drivers/mfd/tps65090.c:tps65090_init",
        "drivers/mfd/aat2870-core.c:aat2870_init",
        "drivers/mfd/palmas.c:palmas_i2c_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_init",
        "drivers/mfd/sec-core.c:sec_pmic_init",
        "drivers/mfd/as3711.c:as3711_i2c_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_init",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_driver_init",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_init",
        "drivers/i2c/i2c-core-base.c:i2c_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587744480,
      "name": "i2c_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int i2c_register_driver(struct module * owner, struct i2c_driver * driver)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
