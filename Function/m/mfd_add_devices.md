# Function: <code>mfd_add_devices</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584656816,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:272",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps65217.c:tps65217_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-core.c:tps65912_device_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/axp20x.c:axp20x_i2c_probe",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584656816,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585005712,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:272",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585005712,
      "name": "mfd_add_devices",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585189168,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:272",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585189168,
      "name": "mfd_add_devices",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585271328,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:272",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585271328,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585699392,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:272",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585699392,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585945440,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:272",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585945440,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586081616,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:272",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586081616,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586316800,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:282",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586316800,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586464976,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:282",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586464976,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587241856,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:261",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_regulator_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:init_regulator",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587241856,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587311024,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:332",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_regulator_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:init_regulator",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587311024,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587198160,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:323",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_regulator_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:init_regulator",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587198160,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587760128,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:325",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_regulator_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:init_regulator",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587760128,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589105376,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:325",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_regulator_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:init_regulator",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589105376,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590642192,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:342",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_regulator_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:init_regulator",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590642192,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590983056,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:312",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_regulator_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:init_regulator",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590983056,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591327024,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:319",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_power_init",
        "drivers/mfd/88pm860x-core.c:device_regulator_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:init_regulator",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591327024,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499332592,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:282",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/sun6i-prcm.c:sun6i_prcm_probe",
        "drivers/mfd/tc3589x.c:tc3589x_probe",
        "drivers/mfd/tc3589x.c:tc3589x_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe",
        "drivers/firmware/xilinx/zynqmp.c:zynqmp_firmware_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499332592,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231882436,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:282",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/tc3589x.c:tc3589x_probe",
        "drivers/mfd/tc3589x.c:tc3589x_probe",
        "drivers/mfd/t7l66xb.c:t7l66xb_probe",
        "drivers/mfd/tc6387xb.c:tc6387xb_probe",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231882436,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292555136,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:282",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/tc3589x.c:tc3589x_probe",
        "drivers/mfd/tc3589x.c:tc3589x_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292555136,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276578204,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:282",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/tc3589x.c:tc3589x_probe",
        "drivers/mfd/tc3589x.c:tc3589x_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276578204,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586194800,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:282",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586194800,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586014080,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:282",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586014080,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586412944,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:282",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586412944,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
int mfd_add_devices(struct device * parent, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586524624,
      "name": "mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:282",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/wm831x-core.c:wm831x_device_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl4030-audio.c:twl4030_audio_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/mfd-core.c:devm_mfd_add_devices",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/da9052-core.c:da9052_device_init",
        "drivers/mfd/lp8788.c:lp8788_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586524624,
      "name": "mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
