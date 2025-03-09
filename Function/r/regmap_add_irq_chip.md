# Function: <code>regmap_add_irq_chip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584529664,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:355",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/axp20x.c:axp20x_i2c_probe",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/da9063-irq.c:da9063_irq_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/sec-irq.c:sec_irq_init",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584529664,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1766
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
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584877696,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:415",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/da9063-irq.c:da9063_irq_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584877696,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2641
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
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585071296,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:415",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/da9063-irq.c:da9063_irq_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585071296,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2641
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
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585153664,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:426",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/da9063-irq.c:da9063_irq_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585153664,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2514
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
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585580640,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:426",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/da9063-irq.c:da9063_irq_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585580640,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2514
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
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585824960,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:426",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/da9063-irq.c:da9063_irq_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585824960,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2507
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
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585959184,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:486",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585959184,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2389
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:564",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586204585,
      "name": "regmap_add_irq_chip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071586201792,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2019
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:559",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586352749,
      "name": "regmap_add_irq_chip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071586350096,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2019
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
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587124080,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:828",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max77836_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587124080,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587209872,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:861",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max77836_init",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587209872,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587098544,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:929",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587098544,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587670544,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:928",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587670544,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589017264,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:930",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589017264,
      "name": "regmap_add_irq_chip",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590544272,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:1108",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
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
      "addr": 18446744071590544272,
      "name": "regmap_add_irq_chip",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590870944,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:920",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
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
      "addr": 18446744071590870944,
      "name": "regmap_add_irq_chip",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591214496,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:920",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
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
      "addr": 18446744071591214496,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499191016,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:559",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
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
      "addr": 18446603336499191016,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2128
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
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231723784,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:559",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
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
      "addr": 3231723784,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2100
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
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292398240,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:559",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
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
      "addr": 13835058055292398240,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2488
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
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276485236,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:559",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
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
      "addr": 18446743936276485236,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1884
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:559",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/da9052-irq.c:da9052_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586114637,
      "name": "regmap_add_irq_chip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071586111984,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2019
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:559",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/da9052-irq.c:da9052_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585960589,
      "name": "regmap_add_irq_chip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071585957936,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2019
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:559",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586300717,
      "name": "regmap_add_irq_chip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071586298064,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2019
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int regmap_add_irq_chip(struct regmap * map, int irq, int irq_flags, int irq_base, const struct regmap_irq_chip * chip, struct regmap_irq_chip_data * * data)
```

```json
{
  "name": "regmap_add_irq_chip",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regmap_add_irq_chip",
      "external": true,
      "loc": "drivers/base/regmap/regmap-irq.c:559",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:devm_regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/mfd/da9052-irq.c:da9052_irq_init",
        "drivers/mfd/da9055-core.c:da9055_device_init",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps65090.c:tps65090_i2c_probe",
        "drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586412173,
      "name": "regmap_add_irq_chip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071586409520,
      "name": "regmap_add_irq_chip",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2019
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
