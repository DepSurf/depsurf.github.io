# Function: <code>regmap_bulk_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584504544,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2410",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/misc/bmp085.c:bmp085_update_raw_temperature",
        "drivers/misc/bmp085.c:show_pressure",
        "drivers/misc/bmp085.c:bmp085_probe",
        "drivers/misc/bmp085.c:bmp085_probe",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm8400-core.c:wm8400_block_read",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584504544,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 727
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
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584851312,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2510",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm8400-core.c:wm8400_block_read",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584851312,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 761
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
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585044848,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2548",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm8400-core.c:wm8400_block_read",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585044848,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 761
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
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585129280,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2553",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm8400-core.c:wm8400_block_read",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585129280,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 761
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
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585555824,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2632",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm8400-core.c:wm8400_block_read",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585555824,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 770
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
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585802464,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2635",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm8400-core.c:wm8400_block_read",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585802464,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585935840,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2795",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm8400-core.c:wm8400_block_read",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585935840,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586177152,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2792",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586177152,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586325664,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2799",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586325664,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587095744,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2794",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_raw_temp",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587095744,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587181792,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2951",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_raw_temp",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587181792,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587069280,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2951",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_raw_temp",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587069280,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2992",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_raw_temp",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592495977,
      "name": "regmap_bulk_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071587640384,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:3009",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_raw_temp",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594366327,
      "name": "regmap_bulk_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071588984144,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 662
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:3158",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_raw_temp",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596249707,
      "name": "regmap_bulk_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071590504928,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 774
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:3188",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_raw_temp",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596778269,
      "name": "regmap_bulk_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071590829104,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 699
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:3076",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_get_raw_temp",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init",
        "drivers/mfd/tps6586x.c:tps6586x_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597687204,
      "name": "regmap_bulk_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071591172160,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 677
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
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499162448,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2799",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499162448,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231698112,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2799",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pinctrl_suspend",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231698112,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292361232,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2799",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292361232,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276461664,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2799",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe",
        "drivers/mfd/tps6586x.c:tps6586x_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276461664,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586088912,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2799",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586088912,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585934864,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2799",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585934864,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586273632,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2799",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586273632,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
int regmap_bulk_read(struct regmap * map, unsigned int reg, void * val, size_t val_count)
```

```json
{
  "name": "regmap_bulk_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586384896,
      "name": "regmap_bulk_read",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2799",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-core.c:arizona_overclocked",
        "drivers/mfd/wm831x-core.c:wm831x_bulk_read",
        "drivers/mfd/twl-core.c:twl_i2c_read",
        "drivers/mfd/lp8788.c:lp8788_read_multi_bytes",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586384896,
      "name": "regmap_bulk_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
