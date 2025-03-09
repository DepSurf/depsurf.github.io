# Function: <code>i2c_smbus_read_byte_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585638672,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2668",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-sx150x.c:sx150x_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8997.c:max8997_read_reg",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8998.c:max8998_read_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/adp5520.c:__adp5520_read",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core.c:acpi_i2c_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585638672,
      "name": "i2c_smbus_read_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586037872,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2873",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-sx150x.c:sx150x_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_read_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_read_reg",
        "drivers/mfd/adp5520.c:__adp5520_read",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core.c:acpi_i2c_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586037872,
      "name": "i2c_smbus_read_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586235312,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:3161",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_read_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_read_reg",
        "drivers/mfd/adp5520.c:__adp5520_read",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235312,
      "name": "i2c_smbus_read_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586329120,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:128",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_read_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_read_reg",
        "drivers/mfd/adp5520.c:__adp5520_read",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586329120,
      "name": "i2c_smbus_read_byte_data",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586793024,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:129",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_read_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_read_reg",
        "drivers/mfd/adp5520.c:__adp5520_read",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586793024,
      "name": "i2c_smbus_read_byte_data",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587066272,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:130",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_read_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_read_reg",
        "drivers/mfd/adp5520.c:__adp5520_read",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587066272,
      "name": "i2c_smbus_read_byte_data",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587226368,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:130",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_read_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_read_reg",
        "drivers/mfd/adp5520.c:__adp5520_read",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587226368,
      "name": "i2c_smbus_read_byte_data",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587493168,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:128",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_read_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_read_reg",
        "drivers/mfd/adp5520.c:__adp5520_read",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587493168,
      "name": "i2c_smbus_read_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587696336,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:128",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_read_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_read_reg",
        "drivers/mfd/adp5520.c:__adp5520_read",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587696336,
      "name": "i2c_smbus_read_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588566306,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:128",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c",
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8998.c:max8998_freeze",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/adp5520.c:adp5520_suspend",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_clr_bits",
        "drivers/mfd/adp5520.c:adp5520_set_bits",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588564752,
      "name": "i2c_smbus_read_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588590946,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:128",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c",
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8998.c:max8998_freeze",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/adp5520.c:adp5520_suspend",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_clr_bits",
        "drivers/mfd/adp5520.c:adp5520_set_bits",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588589392,
      "name": "i2c_smbus_read_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588475042,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:128",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c",
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8998.c:max8998_freeze",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/adp5520.c:adp5520_suspend",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_clr_bits",
        "drivers/mfd/adp5520.c:adp5520_set_bits",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588473488,
      "name": "i2c_smbus_read_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589143250,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:136",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c",
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8998.c:max8998_freeze",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/adp5520.c:adp5520_suspend",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_clr_bits",
        "drivers/mfd/adp5520.c:adp5520_set_bits",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589141696,
      "name": "i2c_smbus_read_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590595273,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:137",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c",
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8998.c:max8998_freeze",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/adp5520.c:adp5520_suspend",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_clr_bits",
        "drivers/mfd/adp5520.c:adp5520_set_bits",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590593264,
      "name": "i2c_smbus_read_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592254361,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:137",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8998.c:max8998_freeze",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/adp5520.c:adp5520_suspend",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_clr_bits",
        "drivers/mfd/adp5520.c:adp5520_set_bits",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592252192,
      "name": "i2c_smbus_read_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592679882,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:137",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8998.c:max8998_freeze",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/adp5520.c:adp5520_suspend",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_clr_bits",
        "drivers/mfd/adp5520.c:adp5520_set_bits",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592677440,
      "name": "i2c_smbus_read_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593425322,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:137",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_freeze",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8998.c:max8998_freeze",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/adp5520.c:adp5520_suspend",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_irq_thread",
        "drivers/mfd/adp5520.c:adp5520_clr_bits",
        "drivers/mfd/adp5520.c:adp5520_set_bits",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593422880,
      "name": "i2c_smbus_read_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500857608,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:128",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/stmpe-i2c.c:i2c_reg_read",
        "drivers/mfd/tc3589x.c:tc3589x_reg_read",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_read_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_read_reg",
        "drivers/mfd/adp5520.c:__adp5520_read",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500857608,
      "name": "i2c_smbus_read_byte_data",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233373496,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:128",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/stmpe-i2c.c:i2c_reg_read",
        "drivers/mfd/tc3589x.c:tc3589x_reg_read",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_read_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_read_reg",
        "drivers/mfd/adp5520.c:__adp5520_read",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233373496,
      "name": "i2c_smbus_read_byte_data",
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
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294324016,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:128",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/stmpe-i2c.c:i2c_reg_read",
        "drivers/mfd/tc3589x.c:tc3589x_reg_read",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_read_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_read_reg",
        "drivers/mfd/adp5520.c:__adp5520_read",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294324016,
      "name": "i2c_smbus_read_byte_data",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277659504,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:128",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/stmpe-i2c.c:i2c_reg_read",
        "drivers/mfd/tc3589x.c:tc3589x_reg_read",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_read_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_read_reg",
        "drivers/mfd/adp5520.c:__adp5520_read",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277659504,
      "name": "i2c_smbus_read_byte_data",
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
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587647584,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:128",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_read_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_read_reg",
        "drivers/mfd/adp5520.c:__adp5520_read",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587647584,
      "name": "i2c_smbus_read_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```

```json
{
  "name": "i2c_smbus_read_byte_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587758864,
      "name": "i2c_smbus_read_byte_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:128",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni",
        "drivers/mfd/da903x.c:da9034_init_chip",
        "drivers/mfd/da903x.c:da9030_read_status",
        "drivers/mfd/da903x.c:da9030_init_chip",
        "drivers/mfd/da903x.c:da903x_update",
        "drivers/mfd/da903x.c:da903x_clr_bits",
        "drivers/mfd/da903x.c:da903x_set_bits",
        "drivers/mfd/da903x.c:da903x_read",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8925-i2c.c:max8925_reg_read",
        "drivers/mfd/max8997.c:max8997_update_reg",
        "drivers/mfd/max8997.c:max8997_read_reg",
        "drivers/mfd/max8998.c:max8998_update_reg",
        "drivers/mfd/max8998.c:max8998_read_reg",
        "drivers/mfd/adp5520.c:__adp5520_read",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587758864,
      "name": "i2c_smbus_read_byte_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client * client, u8 command)
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
