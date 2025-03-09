# Function: <code>regmap_update_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int regmap_update_bits(struct regmap * map, unsigned int reg, unsigned int mask, unsigned int val)
```

```json
{
  "name": "regmap_update_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584507568,
      "name": "regmap_update_bits",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2558",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_input",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_set",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_set",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_output",
        "drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe",
        "drivers/regulator/helpers.c:regulator_enable_regmap",
        "drivers/regulator/helpers.c:regulator_disable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap",
        "drivers/regulator/helpers.c:regulator_set_bypass_regmap",
        "drivers/tty/serial/max310x.c:max310x_md_proc",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_break_ctl",
        "drivers/tty/serial/max310x.c:max310x_gpio_set",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_output",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_output",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_input",
        "drivers/tty/serial/max310x.c:max310x_rs485_config",
        "drivers/tty/serial/max310x.c:max310x_rs485_config",
        "drivers/tty/serial/max310x.c:max310x_rs485_config",
        "drivers/tty/serial/max310x.c:max310x_rs485_config",
        "drivers/tty/serial/max310x.c:max14830_power",
        "drivers/tty/serial/max310x.c:max14830_power",
        "drivers/tty/serial/max310x.c:max310x_power",
        "drivers/tty/serial/max310x.c:max310x_power",
        "drivers/base/regmap/regmap.c:regmap_field_write",
        "drivers/base/regmap/regmap.c:regmap_field_update_bits",
        "drivers/base/regmap/regmap.c:regmap_fields_write",
        "drivers/base/regmap/regmap.c:regmap_fields_update_bits",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-i2c.c:pm860x_set_bits",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-core.c:wm831x_set_bits",
        "drivers/mfd/wm8350-core.c:wm8350_clear_bits",
        "drivers/mfd/wm8350-core.c:wm8350_set_bits",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock",
        "drivers/mfd/tps65910.c:tps65910_power_off",
        "drivers/mfd/tps65910.c:tps65910_power_off",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl6040.c:twl6040_set_bits",
        "drivers/mfd/twl6040.c:twl6040_clear_bits",
        "drivers/mfd/lp8788.c:lp8788_update_bits",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/tps6586x.c:tps6586x_update",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config",
        "drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config",
        "drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config",
        "drivers/mfd/sec-core.c:sec_pmic_shutdown",
        "drivers/mfd/sec-core.c:sec_pmic_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584507568,
      "name": "regmap_update_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regmap_update_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585396773,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/gpio/gpio-crystalcove.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585399295,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_input",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585399925,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/gpio/gpio-rc5t583.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585401673,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/gpio/gpio-tps68470.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_input",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_output",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586249865,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/acpi/pmic/intel_pmic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586251099,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/acpi/pmic/intel_pmic_bytcrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586252212,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/acpi/pmic/intel_pmic_xpower.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586252425,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/acpi/pmic/intel_pmic_bxtwc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586253205,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/acpi/pmic/intel_pmic_chtwc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586253653,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/acpi/pmic/intel_pmic_chtdc_ti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586254309,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/acpi/pmic/tps68470_pmic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586501940,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/regulator/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/helpers.c:regulator_set_current_limit_regmap",
        "drivers/regulator/helpers.c:regulator_set_active_discharge_regmap",
        "drivers/regulator/helpers.c:regulator_set_pull_down_regmap",
        "drivers/regulator/helpers.c:regulator_set_soft_start_regmap",
        "drivers/regulator/helpers.c:regulator_set_bypass_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_disable_regmap",
        "drivers/regulator/helpers.c:regulator_enable_regmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586725313,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_gpio_set_config",
        "drivers/tty/serial/max310x.c:max310x_gpio_set_config",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_output",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_output",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_input",
        "drivers/tty/serial/max310x.c:max310x_gpio_set",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_rs_proc",
        "drivers/tty/serial/max310x.c:max310x_rs_proc",
        "drivers/tty/serial/max310x.c:max310x_set_termios",
        "drivers/tty/serial/max310x.c:max310x_set_termios",
        "drivers/tty/serial/max310x.c:max310x_break_ctl",
        "drivers/tty/serial/max310x.c:max310x_md_proc",
        "drivers/tty/serial/max310x.c:max14830_power",
        "drivers/tty/serial/max310x.c:max310x_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587206410,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587262387,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-i2c.c:pm860x_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587270032,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init"
      ]
    },
    {
      "addr": 18446744071587272268,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587285613,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/wm831x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-core.c:wm831x_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587290589,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/wm8350-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-core.c:wm8350_set_bits",
        "drivers/mfd/wm8350-core.c:wm8350_clear_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587293426,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587294285,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_power_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591505511,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/tps80031.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/tps80031.c:tps80031_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587306069,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_clear_bits",
        "drivers/mfd/twl6040.c:twl6040_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587321941,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/lp8788.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788.c:lp8788_update_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591510494,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591510892,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587342229,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587346949,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/palmas.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/palmas.c:palmas_ext_control_req_config",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587348033,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/rc5t583.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587350379,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_shutdown",
        "drivers/mfd/sec-core.c:sec_pmic_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588607904,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587267728,
      "name": "regmap_update_bits.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regmap_update_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585280917,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/gpio/gpio-crystalcove.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585281997,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_input",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585282629,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/gpio/gpio-rc5t583.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585284345,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/gpio/gpio-tps68470.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_input",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_output",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586125145,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/acpi/pmic/intel_pmic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586126379,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/acpi/pmic/intel_pmic_bytcrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586127491,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/acpi/pmic/intel_pmic_xpower.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586127705,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/acpi/pmic/intel_pmic_bxtwc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586128469,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/acpi/pmic/intel_pmic_chtwc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586128933,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/acpi/pmic/intel_pmic_chtdc_ti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586129589,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/acpi/pmic/tps68470_pmic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586386588,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/regulator/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/helpers.c:regulator_set_ramp_delay_regmap",
        "drivers/regulator/helpers.c:regulator_set_current_limit_regmap",
        "drivers/regulator/helpers.c:regulator_set_active_discharge_regmap",
        "drivers/regulator/helpers.c:regulator_set_pull_down_regmap",
        "drivers/regulator/helpers.c:regulator_set_soft_start_regmap",
        "drivers/regulator/helpers.c:regulator_set_bypass_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_disable_regmap",
        "drivers/regulator/helpers.c:regulator_enable_regmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586608817,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_gpio_set_config",
        "drivers/tty/serial/max310x.c:max310x_gpio_set_config",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_output",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_output",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_input",
        "drivers/tty/serial/max310x.c:max310x_gpio_set",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_rs_proc",
        "drivers/tty/serial/max310x.c:max310x_rs_proc",
        "drivers/tty/serial/max310x.c:max310x_set_termios",
        "drivers/tty/serial/max310x.c:max310x_set_termios",
        "drivers/tty/serial/max310x.c:max310x_break_ctl",
        "drivers/tty/serial/max310x.c:max310x_md_proc",
        "drivers/tty/serial/max310x.c:max14830_power",
        "drivers/tty/serial/max310x.c:max310x_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587092362,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587150819,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-i2c.c:pm860x_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587158322,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/arizona-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_suspend",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_runtime_resume",
        "drivers/mfd/arizona-core.c:arizona_clk32k_disable",
        "drivers/mfd/arizona-core.c:arizona_clk32k_enable"
      ],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init"
      ]
    },
    {
      "addr": 18446744071587160623,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587173241,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/wm831x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-core.c:wm831x_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587177917,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/wm8350-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-core.c:wm8350_set_bits",
        "drivers/mfd/wm8350-core.c:wm8350_clear_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587180834,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587181693,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_power_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591448485,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/tps80031.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/tps80031.c:tps80031_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587193221,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_clear_bits",
        "drivers/mfd/twl6040.c:twl6040_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587208997,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/lp8788.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788.c:lp8788_update_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591454001,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591454397,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587225269,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587229173,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/palmas.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/palmas.c:palmas_ext_control_req_config",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587230209,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/rc5t583.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587232571,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/mfd/sec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/sec-core.c:sec_pmic_shutdown",
        "drivers/mfd/sec-core.c:sec_pmic_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588491643,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1108",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587156064,
      "name": "regmap_update_bits.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regmap_update_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585737485,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/gpio/gpio-crystalcove.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585738624,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_input",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585739320,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/gpio/gpio-rc5t583.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585741065,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/gpio/gpio-tps68470.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_input",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_output",
        "drivers/gpio/gpio-tps68470.c:tps68470_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586625113,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/acpi/pmic/intel_pmic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586626059,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/acpi/pmic/intel_pmic_bytcrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586627668,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/acpi/pmic/intel_pmic_xpower.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586627934,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/acpi/pmic/intel_pmic_bxtwc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586628757,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/acpi/pmic/intel_pmic_chtwc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586629221,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/acpi/pmic/intel_pmic_chtdc_ti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586629877,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/acpi/pmic/tps68470_pmic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586705979,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/clk/versatile/clk-icst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/versatile/clk-icst.c:icst_set_rate",
        "drivers/clk/versatile/clk-icst.c:vco_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586910875,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/regulator/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/helpers.c:regulator_set_ramp_delay_regmap",
        "drivers/regulator/helpers.c:regulator_set_current_limit_regmap",
        "drivers/regulator/helpers.c:regulator_set_active_discharge_regmap",
        "drivers/regulator/helpers.c:regulator_set_pull_down_regmap",
        "drivers/regulator/helpers.c:regulator_set_soft_start_regmap",
        "drivers/regulator/helpers.c:regulator_set_bypass_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_disable_regmap",
        "drivers/regulator/helpers.c:regulator_enable_regmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587152017,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_gpio_set_config",
        "drivers/tty/serial/max310x.c:max310x_gpio_set_config",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_output",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_output",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_input",
        "drivers/tty/serial/max310x.c:max310x_gpio_set",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_rs_proc",
        "drivers/tty/serial/max310x.c:max310x_rs_proc",
        "drivers/tty/serial/max310x.c:max310x_set_termios",
        "drivers/tty/serial/max310x.c:max310x_set_termios",
        "drivers/tty/serial/max310x.c:max310x_break_ctl",
        "drivers/tty/serial/max310x.c:max310x_md_proc",
        "drivers/tty/serial/max310x.c:max14830_power",
        "drivers/tty/serial/max310x.c:max310x_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587664042,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587727203,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-i2c.c:pm860x_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587731977,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/mfd/wm831x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-core.c:wm831x_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587738125,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/mfd/wm8350-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-core.c:wm8350_set_bits",
        "drivers/mfd/wm8350-core.c:wm8350_clear_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587741760,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587742613,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_power_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592510126,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/mfd/tps80031.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/tps80031.c:tps80031_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587755125,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_clear_bits",
        "drivers/mfd/twl6040.c:twl6040_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587771349,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/mfd/lp8788.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788.c:lp8788_update_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592516091,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592516487,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587789765,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587794332,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/mfd/palmas.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/palmas.c:palmas_ext_control_req_config",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587795665,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/mfd/rc5t583.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589160235,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1148",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regmap_update_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586919989,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/gpio/gpio-crystalcove.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586921198,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_input",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586921992,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/gpio/gpio-rc5t583.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587889922,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/acpi/pmic/intel_pmic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587891047,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/acpi/pmic/intel_pmic_bytcrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587892974,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/acpi/pmic/intel_pmic_xpower.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587893262,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/acpi/pmic/intel_pmic_bxtwc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587894213,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/acpi/pmic/intel_pmic_chtwc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587894741,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/acpi/pmic/intel_pmic_chtdc_ti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587895477,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/acpi/pmic/tps68470_pmic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588202973,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/regulator/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/helpers.c:regulator_set_ramp_delay_regmap",
        "drivers/regulator/helpers.c:regulator_set_current_limit_regmap",
        "drivers/regulator/helpers.c:regulator_set_active_discharge_regmap",
        "drivers/regulator/helpers.c:regulator_set_pull_down_regmap",
        "drivers/regulator/helpers.c:regulator_set_soft_start_regmap",
        "drivers/regulator/helpers.c:regulator_set_bypass_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_disable_regmap",
        "drivers/regulator/helpers.c:regulator_enable_regmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588462748,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_gpio_set_config",
        "drivers/tty/serial/max310x.c:max310x_gpio_set_config",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_output",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_output",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_input",
        "drivers/tty/serial/max310x.c:max310x_gpio_set",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_rs_proc",
        "drivers/tty/serial/max310x.c:max310x_rs_proc",
        "drivers/tty/serial/max310x.c:max310x_set_termios",
        "drivers/tty/serial/max310x.c:max310x_set_termios",
        "drivers/tty/serial/max310x.c:max310x_break_ctl",
        "drivers/tty/serial/max310x.c:max310x_md_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589010683,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589071683,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-i2c.c:pm860x_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589077289,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/mfd/wm831x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-core.c:wm831x_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589083773,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/mfd/wm8350-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-core.c:wm8350_set_bits",
        "drivers/mfd/wm8350-core.c:wm8350_clear_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589087680,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589088597,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_power_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589100053,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_clear_bits",
        "drivers/mfd/twl6040.c:twl6040_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589117509,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/mfd/lp8788.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788.c:lp8788_update_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594384968,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594385364,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589137349,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589142332,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/mfd/palmas.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/palmas.c:palmas_ext_control_req_config",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589143880,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/mfd/rc5t583.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590613090,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1173",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regmap_update_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588075189,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/gpio/gpio-crystalcove.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588076702,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_input",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588077624,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/gpio/gpio-rc5t583.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589238655,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/acpi/pmic/intel_pmic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589239943,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/acpi/pmic/intel_pmic_bytcrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589242078,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/acpi/pmic/intel_pmic_xpower.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589242398,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/acpi/pmic/intel_pmic_bxtwc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589243461,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/acpi/pmic/intel_pmic_chtwc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589244117,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/acpi/pmic/intel_pmic_chtdc_ti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589244869,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/acpi/pmic/tps68470_pmic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589608914,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/regulator/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/helpers.c:regulator_set_ramp_delay_regmap",
        "drivers/regulator/helpers.c:regulator_set_current_limit_regmap",
        "drivers/regulator/helpers.c:regulator_set_active_discharge_regmap",
        "drivers/regulator/helpers.c:regulator_set_pull_down_regmap",
        "drivers/regulator/helpers.c:regulator_set_soft_start_regmap",
        "drivers/regulator/helpers.c:regulator_set_bypass_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_disable_regmap",
        "drivers/regulator/helpers.c:regulator_enable_regmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589898940,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_gpio_set_config",
        "drivers/tty/serial/max310x.c:max310x_gpio_set_config",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_output",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_output",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_input",
        "drivers/tty/serial/max310x.c:max310x_gpio_set",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_rs_proc",
        "drivers/tty/serial/max310x.c:max310x_rs_proc",
        "drivers/tty/serial/max310x.c:max310x_set_termios",
        "drivers/tty/serial/max310x.c:max310x_set_termios",
        "drivers/tty/serial/max310x.c:max310x_break_ctl",
        "drivers/tty/serial/max310x.c:max310x_md_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590541764,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590604643,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-i2c.c:pm860x_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590607801,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/mfd/wm831x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-core.c:wm831x_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590617149,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/mfd/wm8350-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-core.c:wm8350_set_bits",
        "drivers/mfd/wm8350-core.c:wm8350_clear_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590623088,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590624181,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_power_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590635973,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_clear_bits",
        "drivers/mfd/twl6040.c:twl6040_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590656837,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/mfd/lp8788.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788.c:lp8788_update_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590663789,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590664797,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590682517,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590689387,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/mfd/palmas.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590692756,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/mfd/rc5t583.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592274418,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1221",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regmap_update_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588349717,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/gpio/gpio-crystalcove.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588351230,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_input",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588352152,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/gpio/gpio-rc5t583.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589535391,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/acpi/pmic/intel_pmic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589536679,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/acpi/pmic/intel_pmic_bytcrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589538814,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/acpi/pmic/intel_pmic_xpower.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589539134,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/acpi/pmic/intel_pmic_bxtwc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589540197,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/acpi/pmic/intel_pmic_chtwc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589540853,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/acpi/pmic/intel_pmic_chtdc_ti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589541621,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/acpi/pmic/tps68470_pmic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589912422,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/regulator/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/helpers.c:regulator_set_ramp_delay_regmap",
        "drivers/regulator/helpers.c:regulator_set_current_limit_regmap",
        "drivers/regulator/helpers.c:regulator_set_active_discharge_regmap",
        "drivers/regulator/helpers.c:regulator_set_pull_down_regmap",
        "drivers/regulator/helpers.c:regulator_set_soft_start_regmap",
        "drivers/regulator/helpers.c:regulator_set_bypass_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_disable_regmap",
        "drivers/regulator/helpers.c:regulator_enable_regmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590208189,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_gpio_set_config",
        "drivers/tty/serial/max310x.c:max310x_gpio_set_config",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_output",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_output",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_input",
        "drivers/tty/serial/max310x.c:max310x_gpio_set",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_rs_proc",
        "drivers/tty/serial/max310x.c:max310x_rs_proc",
        "drivers/tty/serial/max310x.c:max310x_set_termios",
        "drivers/tty/serial/max310x.c:max310x_set_termios",
        "drivers/tty/serial/max310x.c:max310x_break_ctl",
        "drivers/tty/serial/max310x.c:max310x_md_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590869460,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590945763,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-i2c.c:pm860x_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590948897,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/wm831x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-core.c:wm831x_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590958237,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/wm8350-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-core.c:wm8350_set_bits",
        "drivers/mfd/wm8350-core.c:wm8350_clear_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590964064,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590965205,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_power_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590977093,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_clear_bits",
        "drivers/mfd/twl6040.c:twl6040_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590997685,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/lp8788.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788.c:lp8788_update_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591004733,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591005741,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591023605,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591030459,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/palmas.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591033859,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/rc5t583.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592699842,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regmap_update_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588644325,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/gpio/gpio-crystalcove.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_bus_sync_unlock",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588645822,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/gpio/gpio-palmas.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-palmas.c:palmas_gpio_input",
        "drivers/gpio/gpio-palmas.c:palmas_gpio_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588646728,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/gpio/gpio-rc5t583.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_free",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_output",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_dir_input",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set",
        "drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589843727,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/acpi/pmic/intel_pmic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic.c:intel_soc_pmic_exec_mipi_pmic_seq_element"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589845015,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/acpi/pmic/intel_pmic_bytcrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bytcrc.c:intel_crc_pmic_update_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589847150,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/acpi/pmic/intel_pmic_xpower.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589847470,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/acpi/pmic/intel_pmic_bxtwc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_policy",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_aux",
        "drivers/acpi/pmic/intel_pmic_bxtwc.c:intel_bxtwc_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589848533,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/acpi/pmic/intel_pmic_chtwc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_chtwc.c:intel_cht_wc_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589849189,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/acpi/pmic/intel_pmic_chtdc_ti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_update_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589849957,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/acpi/pmic/tps68470_pmic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler",
        "drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590250758,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/regulator/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/helpers.c:regulator_set_ramp_delay_regmap",
        "drivers/regulator/helpers.c:regulator_set_current_limit_regmap",
        "drivers/regulator/helpers.c:regulator_set_active_discharge_regmap",
        "drivers/regulator/helpers.c:regulator_set_pull_down_regmap",
        "drivers/regulator/helpers.c:regulator_set_soft_start_regmap",
        "drivers/regulator/helpers.c:regulator_set_bypass_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap",
        "drivers/regulator/helpers.c:regulator_disable_regmap",
        "drivers/regulator/helpers.c:regulator_enable_regmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590548828,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_gpio_set_config",
        "drivers/tty/serial/max310x.c:max310x_gpio_set_config",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_output",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_output",
        "drivers/tty/serial/max310x.c:max310x_gpio_direction_input",
        "drivers/tty/serial/max310x.c:max310x_gpio_set",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_startup",
        "drivers/tty/serial/max310x.c:max310x_rs_proc",
        "drivers/tty/serial/max310x.c:max310x_rs_proc",
        "drivers/tty/serial/max310x.c:max310x_set_termios",
        "drivers/tty/serial/max310x.c:max310x_set_termios",
        "drivers/tty/serial/max310x.c:max310x_break_ctl",
        "drivers/tty/serial/max310x.c:max310x_md_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591213011,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591289571,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-i2c.c:pm860x_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591292705,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/wm831x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-core.c:wm831x_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591302077,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/wm8350-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-core.c:wm8350_set_bits",
        "drivers/mfd/wm8350-core.c:wm8350_clear_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591307904,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_sync_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591309045,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_power_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591321061,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_clear_bits",
        "drivers/mfd/twl6040.c:twl6040_set_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591341701,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/lp8788.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788.c:lp8788_update_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591348717,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/max77693.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77693.c:max77693_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591349725,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/max77843.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max77843.c:max77843_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591367653,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591374872,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/palmas.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config",
        "drivers/mfd/palmas.c:palmas_ext_control_req_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591378275,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/mfd/rc5t583.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583.c:rc5t583_ext_power_req_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593446652,
      "name": "regmap_update_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1238",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_read",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
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
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int regmap_update_bits(struct regmap * map, unsigned int reg, unsigned int mask, unsigned int val)
```
</details>
</li>
</ul>
