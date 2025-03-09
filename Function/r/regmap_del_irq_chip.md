# Function: <code>regmap_del_irq_chip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584529344,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:560",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/tps65910.c:tps65910_i2c_remove",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/axp20x.c:axp20x_i2c_remove",
        "drivers/mfd/axp20x.c:axp20x_i2c_probe",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9063-irq.c:da9063_irq_exit",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_remove",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_remove",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/sec-irq.c:sec_irq_exit",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584529344,
      "name": "regmap_del_irq_chip",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584877405,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:669",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9063-irq.c:da9063_irq_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_remove",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584877104,
      "name": "regmap_del_irq_chip.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071584877344,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585071005,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:669",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9063-irq.c:da9063_irq_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_remove",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585070704,
      "name": "regmap_del_irq_chip.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071585070944,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585153496,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:680",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9063-irq.c:da9063_irq_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_remove",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585153232,
      "name": "regmap_del_irq_chip.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071585153456,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585580472,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:680",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9063-irq.c:da9063_irq_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_remove",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585580208,
      "name": "regmap_del_irq_chip.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071585580432,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585824792,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:680",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/da9063-irq.c:da9063_irq_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_remove",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585824528,
      "name": "regmap_del_irq_chip.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071585824752,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585959016,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:742",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_remove",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585958752,
      "name": "regmap_del_irq_chip.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071585958976,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586201560,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:826",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586201296,
      "name": "regmap_del_irq_chip.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071586201520,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586349928,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:821",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586349664,
      "name": "regmap_del_irq_chip.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071586349888,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587120584,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:845",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587120320,
      "name": "regmap_del_irq_chip.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071587120544,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587206184,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:878",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587205920,
      "name": "regmap_del_irq_chip.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071587206144,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587092136,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:946",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587091856,
      "name": "regmap_del_irq_chip.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071587092096,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587664408,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:945",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587664064,
      "name": "regmap_del_irq_chip.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071587664368,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589011096,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:947",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589010720,
      "name": "regmap_del_irq_chip.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071589011040,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590538792,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:1125",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590538320,
      "name": "regmap_del_irq_chip.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    },
    {
      "addr": 18446744071590538720,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590867816,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:937",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590867344,
      "name": "regmap_del_irq_chip.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
    },
    {
      "addr": 18446744071590867744,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591211320,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:937",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591210848,
      "name": "regmap_del_irq_chip.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
    },
    {
      "addr": 18446744071591211248,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499190876,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:821",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499190560,
      "name": "regmap_del_irq_chip.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446603336499190792,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231723544,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:821",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231723284,
      "name": "regmap_del_irq_chip.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 3231723484,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292398100,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:821",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292397728,
      "name": "regmap_del_irq_chip.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 13835058055292398048,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276485124,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:821",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276484808,
      "name": "regmap_del_irq_chip.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446743936276485048,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586111816,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:821",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586111552,
      "name": "regmap_del_irq_chip.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071586111776,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585957768,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:821",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585957504,
      "name": "regmap_del_irq_chip.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071585957728,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586297896,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:821",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586297632,
      "name": "regmap_del_irq_chip.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071586297856,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void regmap_del_irq_chip(int irq, struct regmap_irq_chip_data * d)
```

```json
{
  "name": "regmap_del_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586409352,
      "name": "regmap_del_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:821",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_exit",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65912-core.c:tps65912_device_exit",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_remove",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_exit",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_exit",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_remove",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586409088,
      "name": "regmap_del_irq_chip.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071586409312,
      "name": "regmap_del_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
