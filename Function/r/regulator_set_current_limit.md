# Function: <code>regulator_set_current_limit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583929808,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:3162",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583929808,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584266576,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:3195",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584266576,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584448336,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:3228",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584448336,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584530816,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:3251",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584530816,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584941008,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:3259",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584941008,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:3433",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585187803,
      "name": "regulator_set_current_limit.cold.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071585173168,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:4040",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585304609,
      "name": "regulator_set_current_limit.cold.59",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071585288208,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:4060",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585516894,
      "name": "regulator_set_current_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585494784,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:4070",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585658520,
      "name": "regulator_set_current_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585642016,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:4110",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/charger-manager.c:charger_extcon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586382886,
      "name": "regulator_set_current_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071586367168,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:4248",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/charger-manager.c:charger_extcon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591455056,
      "name": "regulator_set_current_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071586486096,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:4250",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/charger-manager.c:charger_extcon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591396844,
      "name": "regulator_set_current_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071586369536,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:4373",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/charger-manager.c:charger_extcon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592441419,
      "name": "regulator_set_current_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071586884016,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:4418",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/charger-manager.c:charger_extcon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594309710,
      "name": "regulator_set_current_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071588172608,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589577184,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:4448",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/charger-manager.c:charger_extcon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589577184,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589879104,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:4514",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/charger-manager.c:charger_extcon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589879104,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590216960,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:4520",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/charger-manager.c:charger_extcon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590216960,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498298632,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:4070",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498298632,
      "name": "regulator_set_current_limit",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230983752,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:4070",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230983752,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291470896,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:4070",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291470896,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275995056,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:4070",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275995056,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:4070",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585419441,
      "name": "regulator_set_current_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585402976,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:4070",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585289592,
      "name": "regulator_set_current_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585273088,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:4070",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585608920,
      "name": "regulator_set_current_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585592416,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
int regulator_set_current_limit(struct regulator * regulator, int min_uA, int max_uA)
```

```json
{
  "name": "regulator_set_current_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_set_current_limit",
      "external": true,
      "loc": "drivers/regulator/core.c:4070",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585717048,
      "name": "regulator_set_current_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585700544,
      "name": "regulator_set_current_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
