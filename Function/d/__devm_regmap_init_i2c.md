# Function: <code>__devm_regmap_init_i2c</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584525280,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:300",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65217.c:tps65217_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/axp20x.c:axp20x_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584525280,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584872320,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:300",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584872320,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585065872,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:300",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585065872,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585148336,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:300",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585148336,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585575296,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:300",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585575296,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585819520,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:296",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585819520,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585953472,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:296",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585953472,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586195824,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:292",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586195824,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586344128,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:292",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586344128,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587115488,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:353",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max77836_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587115488,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587200576,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:353",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max77836_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587200576,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587088000,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:353",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587088000,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587659904,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:384",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587659904,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589005552,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:384",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589005552,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590528752,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:384",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_i2c_probe",
        "drivers/tty/serial/max310x.c:max310x_i2c_probe",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590528752,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590856704,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:384",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_i2c_probe",
        "drivers/tty/serial/max310x.c:max310x_i2c_probe",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590856704,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591200336,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:384",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/max310x.c:max310x_i2c_probe",
        "drivers/tty/serial/max310x.c:max310x_i2c_probe",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591200336,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499183192,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:292",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77620.c:max77620_probe",
        "drivers/mfd/max77686.c:max77686_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/as3722.c:as3722_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499183192,
      "name": "__devm_regmap_init_i2c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231717068,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:292",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65217.c:tps65217_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77620.c:max77620_probe",
        "drivers/mfd/max77686.c:max77686_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/as3722.c:as3722_i2c_probe",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231717068,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292388864,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:292",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77620.c:max77620_probe",
        "drivers/mfd/max77686.c:max77686_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/as3722.c:as3722_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292388864,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276478178,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:292",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77620.c:max77620_probe",
        "drivers/mfd/max77686.c:max77686_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/as3722.c:as3722_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276478178,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586292096,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:292",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586292096,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```

```json
{
  "name": "__devm_regmap_init_i2c",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586403552,
      "name": "__devm_regmap_init_i2c",
      "external": true,
      "loc": "drivers/base/regmap/regmap-i2c.c:292",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-i2c.c:da9055_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586403552,
      "name": "__devm_regmap_init_i2c",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct regmap * __devm_regmap_init_i2c(struct i2c_client * i2c, const struct regmap_config * config, struct lock_class_key * lock_key, const char * lock_name)
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
