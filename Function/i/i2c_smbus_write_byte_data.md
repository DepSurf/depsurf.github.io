# Function: <code>i2c_smbus_write_byte_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585638784,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2689",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:acpi_i2c_space_handler"
      ],
      "caller_func": [
        "drivers/gpio/gpio-sx150x.c:sx150x_i2c_write",
        "drivers/gpio/gpio-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-sx150x.c:sx150x_probe",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/max8997.c:max8997_write_reg",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8998.c:max8998_write_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/adp5520.c:__adp5520_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585638784,
      "name": "i2c_smbus_write_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586048019,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2894",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:acpi_i2c_space_handler"
      ],
      "caller_func": [
        "drivers/gpio/gpio-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-sx150x.c:sx150x_i2c_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_write_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_write_reg",
        "drivers/mfd/adp5520.c:__adp5520_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586037984,
      "name": "i2c_smbus_write_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586245587,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:3182",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_acpi_space_handler"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_write_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_write_reg",
        "drivers/mfd/adp5520.c:__adp5520_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235424,
      "name": "i2c_smbus_write_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586329232,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:149",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_write_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_write_reg",
        "drivers/mfd/adp5520.c:__adp5520_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586329232,
      "name": "i2c_smbus_write_byte_data",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586793136,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:150",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_write_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_write_reg",
        "drivers/mfd/adp5520.c:__adp5520_write",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586793136,
      "name": "i2c_smbus_write_byte_data",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587066384,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:151",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_write_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_write_reg",
        "drivers/mfd/adp5520.c:__adp5520_write",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587066384,
      "name": "i2c_smbus_write_byte_data",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587226480,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:151",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_write_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_write_reg",
        "drivers/mfd/adp5520.c:__adp5520_write",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587226480,
      "name": "i2c_smbus_write_byte_data",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587493280,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:149",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_write_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_write_reg",
        "drivers/mfd/adp5520.c:__adp5520_write",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587493280,
      "name": "i2c_smbus_write_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587696448,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:149",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_write_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_write_reg",
        "drivers/mfd/adp5520.c:__adp5520_write",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587696448,
      "name": "i2c_smbus_write_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588564864,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:149",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read_reg16",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8998.c:max8998_restore",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/adp5520.c:adp5520_resume",
        "drivers/mfd/adp5520.c:adp5520_suspend",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_clr_bits",
        "drivers/mfd/adp5520.c:adp5520_set_bits",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588564864,
      "name": "i2c_smbus_write_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588589504,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:149",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read_reg16",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8998.c:max8998_restore",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/adp5520.c:adp5520_resume",
        "drivers/mfd/adp5520.c:adp5520_suspend",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_clr_bits",
        "drivers/mfd/adp5520.c:adp5520_set_bits",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588589504,
      "name": "i2c_smbus_write_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588473600,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:149",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read_reg16",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8998.c:max8998_restore",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/adp5520.c:adp5520_resume",
        "drivers/mfd/adp5520.c:adp5520_suspend",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_clr_bits",
        "drivers/mfd/adp5520.c:adp5520_set_bits",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588473600,
      "name": "i2c_smbus_write_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589141808,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:157",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read_reg16",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8998.c:max8998_restore",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/adp5520.c:adp5520_resume",
        "drivers/mfd/adp5520.c:adp5520_suspend",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_clr_bits",
        "drivers/mfd/adp5520.c:adp5520_set_bits",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589141808,
      "name": "i2c_smbus_write_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590593424,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:158",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read_reg16",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8998.c:max8998_restore",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/adp5520.c:adp5520_resume",
        "drivers/mfd/adp5520.c:adp5520_suspend",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_clr_bits",
        "drivers/mfd/adp5520.c:adp5520_set_bits",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590593424,
      "name": "i2c_smbus_write_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592252368,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:158",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read_reg16",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8998.c:max8998_restore",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/adp5520.c:adp5520_resume",
        "drivers/mfd/adp5520.c:adp5520_suspend",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_clr_bits",
        "drivers/mfd/adp5520.c:adp5520_set_bits",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592252368,
      "name": "i2c_smbus_write_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592677616,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:158",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read_reg16",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8998.c:max8998_restore",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/adp5520.c:adp5520_resume",
        "drivers/mfd/adp5520.c:adp5520_suspend",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_clr_bits",
        "drivers/mfd/adp5520.c:adp5520_set_bits",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592677616,
      "name": "i2c_smbus_write_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593423056,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:158",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read_reg16",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_restore",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8998.c:max8998_restore",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/adp5520.c:adp5520_resume",
        "drivers/mfd/adp5520.c:adp5520_suspend",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_clr_bits",
        "drivers/mfd/adp5520.c:adp5520_set_bits",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593423056,
      "name": "i2c_smbus_write_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500857736,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:149",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/stmpe-i2c.c:i2c_reg_write",
        "drivers/mfd/tc3589x.c:tc3589x_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_write_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_write_reg",
        "drivers/mfd/adp5520.c:__adp5520_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500857736,
      "name": "i2c_smbus_write_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233373624,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:149",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/stmpe-i2c.c:i2c_reg_write",
        "drivers/mfd/tc3589x.c:tc3589x_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_write_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_write_reg",
        "drivers/mfd/adp5520.c:__adp5520_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233373624,
      "name": "i2c_smbus_write_byte_data",
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
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294324144,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:149",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/stmpe-i2c.c:i2c_reg_write",
        "drivers/mfd/tc3589x.c:tc3589x_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_write_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_write_reg",
        "drivers/mfd/adp5520.c:__adp5520_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294324144,
      "name": "i2c_smbus_write_byte_data",
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
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277659578,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:149",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/stmpe-i2c.c:i2c_reg_write",
        "drivers/mfd/tc3589x.c:tc3589x_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_write_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_write_reg",
        "drivers/mfd/adp5520.c:__adp5520_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277659578,
      "name": "i2c_smbus_write_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587647696,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:149",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_write_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_write_reg",
        "drivers/mfd/adp5520.c:__adp5520_write",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587647696,
      "name": "i2c_smbus_write_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587758976,
      "name": "i2c_smbus_write_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:149",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_write",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_write_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_write_reg",
        "drivers/mfd/adp5520.c:__adp5520_write",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587758976,
      "name": "i2c_smbus_write_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client * client, u8 command, u8 value)
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
