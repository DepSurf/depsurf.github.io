# Function: <code>i2c_del_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585634320,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:1909",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-sx150x.c:sx150x_exit",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_exit",
        "drivers/mfd/wm8400-core.c:wm8400_module_exit",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_exit",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_exit",
        "drivers/mfd/tps65217.c:tps65217_exit",
        "drivers/mfd/tps65910.c:tps65910_i2c_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_exit",
        "drivers/mfd/tps80031.c:tps80031_exit",
        "drivers/mfd/twl-core.c:twl_driver_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/axp20x.c:axp20x_i2c_driver_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77693.c:max77693_i2c_exit",
        "drivers/mfd/max77843.c:max77843_i2c_exit",
        "drivers/mfd/max8925-i2c.c:max8925_i2c_exit",
        "drivers/mfd/max8997.c:max8997_i2c_exit",
        "drivers/mfd/max8998.c:max8998_i2c_exit",
        "drivers/mfd/ab3100-core.c:ab3100_i2c_exit",
        "drivers/mfd/adp5520.c:adp5520_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/tps65090.c:tps65090_exit",
        "drivers/mfd/aat2870-core.c:aat2870_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_exit",
        "drivers/mfd/sec-core.c:sec_pmic_exit",
        "drivers/mfd/as3711.c:as3711_i2c_exit",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit",
        "drivers/i2c/i2c-core.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585634320,
      "name": "i2c_del_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586033536,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2106",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_exit",
        "drivers/mfd/wm8400-core.c:wm8400_module_exit",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_exit",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_exit",
        "drivers/mfd/tps65910.c:tps65910_i2c_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/tps80031.c:tps80031_exit",
        "drivers/mfd/twl-core.c:twl_driver_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/ab3100-core.c:ab3100_i2c_exit",
        "drivers/mfd/adp5520.c:adp5520_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/tps65090.c:tps65090_exit",
        "drivers/mfd/aat2870-core.c:aat2870_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_exit",
        "drivers/mfd/sec-core.c:sec_pmic_exit",
        "drivers/mfd/as3711.c:as3711_i2c_exit",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit",
        "drivers/i2c/i2c-core.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586033536,
      "name": "i2c_del_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586230976,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2391",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_exit",
        "drivers/mfd/wm8400-core.c:wm8400_module_exit",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_exit",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_exit",
        "drivers/mfd/tps65910.c:tps65910_i2c_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/tps80031.c:tps80031_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/adp5520.c:adp5520_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/tps65090.c:tps65090_exit",
        "drivers/mfd/aat2870-core.c:aat2870_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_exit",
        "drivers/mfd/sec-core.c:sec_pmic_exit",
        "drivers/mfd/as3711.c:as3711_i2c_exit",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit",
        "drivers/i2c/i2c-core.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586230976,
      "name": "i2c_del_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586317072,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1633",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_exit",
        "drivers/mfd/wm8400-core.c:wm8400_module_exit",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_exit",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_exit",
        "drivers/mfd/tps65910.c:tps65910_i2c_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/tps80031.c:tps80031_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/adp5520.c:adp5520_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/tps65090.c:tps65090_exit",
        "drivers/mfd/aat2870-core.c:aat2870_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_exit",
        "drivers/mfd/sec-core.c:sec_pmic_exit",
        "drivers/mfd/as3711.c:as3711_i2c_exit",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586317072,
      "name": "i2c_del_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586780736,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1657",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_exit",
        "drivers/mfd/wm8400-core.c:wm8400_module_exit",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_exit",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_exit",
        "drivers/mfd/tps65910.c:tps65910_i2c_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/tps80031.c:tps80031_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/adp5520.c:adp5520_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/tps65090.c:tps65090_exit",
        "drivers/mfd/aat2870-core.c:aat2870_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_exit",
        "drivers/mfd/sec-core.c:sec_pmic_exit",
        "drivers/mfd/as3711.c:as3711_i2c_exit",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586780736,
      "name": "i2c_del_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587053728,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1636",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_exit",
        "drivers/mfd/wm8400-core.c:wm8400_module_exit",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_exit",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_exit",
        "drivers/mfd/tps65910.c:tps65910_i2c_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/tps80031.c:tps80031_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/adp5520.c:adp5520_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/tps65090.c:tps65090_exit",
        "drivers/mfd/aat2870-core.c:aat2870_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_exit",
        "drivers/mfd/sec-core.c:sec_pmic_exit",
        "drivers/mfd/as3711.c:as3711_i2c_exit",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587053728,
      "name": "i2c_del_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587213792,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1641",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_exit",
        "drivers/mfd/wm8400-core.c:wm8400_module_exit",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_exit",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_exit",
        "drivers/mfd/tps65910.c:tps65910_i2c_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/tps80031.c:tps80031_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/adp5520.c:adp5520_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/tps65090.c:tps65090_exit",
        "drivers/mfd/aat2870-core.c:aat2870_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_exit",
        "drivers/mfd/sec-core.c:sec_pmic_exit",
        "drivers/mfd/as3711.c:as3711_i2c_exit",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587213792,
      "name": "i2c_del_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587479104,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1731",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/sec-core.c:sec_pmic_exit",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587479104,
      "name": "i2c_del_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587682272,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1736",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/sec-core.c:sec_pmic_exit",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587682272,
      "name": "i2c_del_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588548000,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1698",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/sec-core.c:sec_pmic_exit",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588548000,
      "name": "i2c_del_driver",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588573552,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1828",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/sec-core.c:sec_pmic_exit",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588573552,
      "name": "i2c_del_driver",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588457088,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1888",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/sec-core.c:sec_pmic_driver_exit",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588457088,
      "name": "i2c_del_driver",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589125168,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1889",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589125168,
      "name": "i2c_del_driver",
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
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590576288,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1892",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590576288,
      "name": "i2c_del_driver",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592232768,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1886",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_driver_exit",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592232768,
      "name": "i2c_del_driver",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592658624,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1999",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_driver_exit",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592658624,
      "name": "i2c_del_driver",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593403792,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2014",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_uart_exit",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_driver_exit",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593403792,
      "name": "i2c_del_driver",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500838456,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1736",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/stmpe-i2c.c:stmpe_exit",
        "drivers/mfd/tc3589x.c:tc3589x_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77686.c:max77686_i2c_driver_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/sec-core.c:sec_pmic_exit",
        "drivers/mfd/as3722.c:as3722_i2c_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500838456,
      "name": "i2c_del_driver",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233358008,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1736",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/stmpe-i2c.c:stmpe_exit",
        "drivers/mfd/tc3589x.c:tc3589x_exit",
        "drivers/mfd/tps65217.c:tps65217_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77686.c:max77686_i2c_driver_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/sec-core.c:sec_pmic_exit",
        "drivers/mfd/as3722.c:as3722_i2c_driver_exit",
        "drivers/rtc/rtc-pcf8523.c:pcf8523_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_driver_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233358008,
      "name": "i2c_del_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294303792,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1736",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_i2c_atmel.c:i2c_atmel_driver_exit",
        "drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_driver_exit",
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_driver_exit",
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/stmpe-i2c.c:stmpe_exit",
        "drivers/mfd/tc3589x.c:tc3589x_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77686.c:max77686_i2c_driver_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/sec-core.c:sec_pmic_exit",
        "drivers/mfd/as3722.c:as3722_i2c_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294303792,
      "name": "i2c_del_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277646502,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1736",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/stmpe-i2c.c:stmpe_exit",
        "drivers/mfd/tc3589x.c:tc3589x_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77686.c:max77686_i2c_driver_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/sec-core.c:sec_pmic_exit",
        "drivers/mfd/as3722.c:as3722_i2c_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277646502,
      "name": "i2c_del_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587633520,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1736",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/sec-core.c:sec_pmic_exit",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587633520,
      "name": "i2c_del_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void i2c_del_driver(struct i2c_driver * driver)
```

```json
{
  "name": "i2c_del_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587744640,
      "name": "i2c_del_driver",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1736",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_i2c_exit",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_driver_exit",
        "drivers/mfd/twl6040.c:twl6040_driver_exit",
        "drivers/mfd/da903x.c:da903x_exit",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_exit",
        "drivers/mfd/lp8788.c:lp8788_exit",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_exit",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_driver_exit",
        "drivers/mfd/max14577.c:max14577_i2c_exit",
        "drivers/mfd/max77693.c:max77693_i2c_driver_exit",
        "drivers/mfd/tps6586x.c:tps6586x_exit",
        "drivers/mfd/palmas.c:palmas_i2c_exit",
        "drivers/mfd/sec-core.c:sec_pmic_exit",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_driver_exit",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_driver_exit",
        "drivers/i2c/i2c-core-base.c:i2c_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587744640,
      "name": "i2c_del_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void i2c_del_driver(struct i2c_driver * driver)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void i2c_del_driver(struct i2c_driver * driver)
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
