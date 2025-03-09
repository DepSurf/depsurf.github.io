# Function: <code>regulator_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583942880,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1645",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/power/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583942880,
      "name": "regulator_get",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584277664,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1697",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/power/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584277664,
      "name": "regulator_get",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584457254,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1698",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/regulator/devres.c:_devm_regulator_get",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584457136,
      "name": "regulator_get",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584547116,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1708",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584546992,
      "name": "regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584957372,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1708",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584957248,
      "name": "regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585186400,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1759",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585186400,
      "name": "regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585302784,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1984",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585302784,
      "name": "regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585508559,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1966",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585508432,
      "name": "regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585657247,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1974",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585657120,
      "name": "regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586376895,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1993",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/power/supply/charger-manager.c:charger_manager_register_extcon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586376768,
      "name": "regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586494812,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:2050",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/power/supply/charger-manager.c:charger_manager_register_extcon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586494688,
      "name": "regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586377836,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:2061",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/power/supply/charger-manager.c:charger_manager_register_extcon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586377712,
      "name": "regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586901292,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:2161",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/power/supply/charger-manager.c:charger_manager_register_extcon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586901168,
      "name": "regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588194010,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:2208",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/power/supply/charger-manager.c:charger_manager_register_extcon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588193888,
      "name": "regulator_get",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589594688,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:2235",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/charger-manager.c:charger_manager_register_extcon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589594688,
      "name": "regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589898048,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:2301",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/charger-manager.c:charger_manager_register_extcon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589898048,
      "name": "regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590235792,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:2303",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/charger-manager.c:charger_manager_register_extcon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590235792,
      "name": "regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498319720,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1974",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/ata/libahci_platform.c:ahci_platform_get_resources",
        "drivers/ata/libahci_platform.c:ahci_platform_get_resources",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498319552,
      "name": "regulator_get",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231000868,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1974",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/ata/libahci_platform.c:ahci_platform_get_resources",
        "drivers/ata/libahci_platform.c:ahci_platform_get_resources",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231000740,
      "name": "regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291495148,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1974",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291494960,
      "name": "regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276009446,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1974",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276009300,
      "name": "regulator_get",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585418239,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1974",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585418112,
      "name": "regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585288319,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1974",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585288192,
      "name": "regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585607647,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1974",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585607520,
      "name": "regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct regulator * regulator_get(struct device * dev, const char * id)
```

```json
{
  "name": "regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585715775,
      "name": "regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1974",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_bulk_get"
      ],
      "caller_func": [
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585715648,
      "name": "regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
