# Function: <code>devm_mfd_add_devices</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585006000,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:349",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585006000,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585189456,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:349",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585189456,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585271600,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:349",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585271600,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585699664,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:349",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585699664,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585945728,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:349",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585945728,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586081904,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:349",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586081904,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586317040,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:359",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586317040,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586465216,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:359",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586465216,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587242016,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:322",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587242016,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587311232,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:417",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587311232,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587198368,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:411",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587198368,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587760336,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:413",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587760336,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589105600,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:413",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589105600,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590642432,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:437",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590642432,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590983296,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:407",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590983296,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591327264,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:414",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591327264,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499332928,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:359",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/bcm2835-pm.c:bcm2835_pm_probe",
        "drivers/mfd/bcm2835-pm.c:bcm2835_pm_probe",
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/max77620.c:max77620_probe",
        "drivers/mfd/max77686.c:max77686_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/as3722.c:as3722_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499332928,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231882712,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:359",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_i2c_probe",
        "drivers/mfd/tps65217.c:tps65217_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/max77620.c:max77620_probe",
        "drivers/mfd/max77686.c:max77686_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/as3722.c:as3722_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231882712,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292555632,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:359",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/max77620.c:max77620_probe",
        "drivers/mfd/max77686.c:max77686_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/as3722.c:as3722_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292555632,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276578404,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:359",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/max77620.c:max77620_probe",
        "drivers/mfd/max77686.c:max77686_i2c_probe",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/as3722.c:as3722_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276578404,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586195040,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:359",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586195040,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586014320,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:359",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586014320,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586413184,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:359",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586413184,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```

```json
{
  "name": "devm_mfd_add_devices",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586524864,
      "name": "devm_mfd_add_devices",
      "external": true,
      "loc": "drivers/mfd/mfd-core.c:359",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm8400-core.c:wm8400_register_codec",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps68470.c:tps68470_probe",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/da9063-core.c:da9063_device_init",
        "drivers/mfd/rc5t583.c:rc5t583_i2c_probe",
        "drivers/mfd/sec-core.c:sec_pmic_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586524864,
      "name": "devm_mfd_add_devices",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int devm_mfd_add_devices(struct device * dev, int id, const struct mfd_cell * cells, int n_devs, struct resource * mem_base, int irq_base, struct irq_domain * domain)
```
</details>
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
