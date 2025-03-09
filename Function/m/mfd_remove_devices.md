# Function: <code>mfd_remove_devices</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584655008,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:328",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_remove",
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/tps65217.c:tps65217_remove",
        "drivers/mfd/tps65910.c:tps65910_i2c_remove",
        "drivers/mfd/tps65912-core.c:tps65912_device_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/mfd-core.c:mfd_add_devices",
        "drivers/mfd/smsc-ece1099.c:smsc_i2c_remove",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/axp20x.c:axp20x_i2c_remove",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9063-core.c:da9063_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_remove",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8997.c:max8997_i2c_remove",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_remove",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_remove",
        "drivers/mfd/sec-core.c:sec_pmic_remove",
        "drivers/mfd/as3711.c:as3711_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584655008,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585003600,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:328",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release",
        "drivers/mfd/mfd-core.c:mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585003600,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585187056,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:328",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release",
        "drivers/mfd/mfd-core.c:mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585187056,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585269248,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:328",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release",
        "drivers/mfd/mfd-core.c:mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585269248,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585697344,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:328",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release",
        "drivers/mfd/mfd-core.c:mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585697344,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585943440,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:328",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release",
        "drivers/mfd/mfd-core.c:mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585943440,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586079616,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:328",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_exit",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release",
        "drivers/mfd/mfd-core.c:mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586079616,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586315024,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:338",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release",
        "drivers/mfd/mfd-core.c:mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586315024,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586463200,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:338",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release",
        "drivers/mfd/mfd-core.c:mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586463200,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587242254,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:304",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_msic.c:intel_msic_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587240336,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587311519,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:387",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_msic.c:intel_msic_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587309264,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587198646,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:381",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587196432,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587760621,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:383",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587758368,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589105911,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:383",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589103472,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590642743,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:407",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590640128,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590983604,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:377",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590981232,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591327572,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:384",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591325200,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499330792,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:338",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/stmpe.c:stmpe_remove",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/tc3589x.c:tc3589x_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release",
        "drivers/mfd/mfd-core.c:mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_firmware_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499330792,
      "name": "mfd_remove_devices",
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231880980,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:338",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/asic3.c:asic3_remove",
        "drivers/mfd/stmpe.c:stmpe_remove",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/tc3589x.c:tc3589x_remove",
        "drivers/mfd/t7l66xb.c:t7l66xb_remove",
        "drivers/mfd/tc6387xb.c:tc6387xb_remove",
        "drivers/mfd/tc6393xb.c:tc6393xb_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release",
        "drivers/mfd/mfd-core.c:mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231880980,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292553632,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:338",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/stmpe.c:stmpe_remove",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/tc3589x.c:tc3589x_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release",
        "drivers/mfd/mfd-core.c:mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292553632,
      "name": "mfd_remove_devices",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276576970,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:338",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/stmpe.c:stmpe_remove",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/tc3589x.c:tc3589x_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release",
        "drivers/mfd/mfd-core.c:mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276576970,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586193024,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:338",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release",
        "drivers/mfd/mfd-core.c:mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586193024,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586012304,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:338",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release",
        "drivers/mfd/mfd-core.c:mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586012304,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586411168,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:338",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release",
        "drivers/mfd/mfd-core.c:mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586411168,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void mfd_remove_devices(struct device * parent)
```

```json
{
  "name": "mfd_remove_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586522848,
      "name": "mfd_remove_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:338",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_exit",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_remove",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/mfd-core.c:devm_mfd_dev_release",
        "drivers/mfd/mfd-core.c:mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_exit",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_remove",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_exit",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_remove",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586522848,
      "name": "mfd_remove_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
