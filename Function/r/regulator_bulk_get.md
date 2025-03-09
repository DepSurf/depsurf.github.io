# Function: <code>regulator_bulk_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583942912,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:3444",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583942912,
      "name": "regulator_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584277760,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:3476",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584277760,
      "name": "regulator_bulk_get",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584457168,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:3542",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584457168,
      "name": "regulator_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584547024,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:3565",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584547024,
      "name": "regulator_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584957280,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:3573",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584957280,
      "name": "regulator_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585186432,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:3747",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585186432,
      "name": "regulator_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585302816,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:4372",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585302816,
      "name": "regulator_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:4392",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585517802,
      "name": "regulator_bulk_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585508464,
      "name": "regulator_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:4402",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585659596,
      "name": "regulator_bulk_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585657152,
      "name": "regulator_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:4451",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586384166,
      "name": "regulator_bulk_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586376800,
      "name": "regulator_bulk_get",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:4589",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591456393,
      "name": "regulator_bulk_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586494720,
      "name": "regulator_bulk_get",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:4591",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591398180,
      "name": "regulator_bulk_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586377744,
      "name": "regulator_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:4728",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592443218,
      "name": "regulator_bulk_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586901200,
      "name": "regulator_bulk_get",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:4773",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594312137,
      "name": "regulator_bulk_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588193920,
      "name": "regulator_bulk_get",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589604848,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:4842",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589604848,
      "name": "regulator_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589908224,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:4908",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589908224,
      "name": "regulator_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590246144,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:4930",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590246144,
      "name": "regulator_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498319608,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:4402",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498319608,
      "name": "regulator_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231000772,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:4402",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get",
        "sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231000772,
      "name": "regulator_bulk_get",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291494992,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:4402",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291494992,
      "name": "regulator_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276009352,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:4402",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276009352,
      "name": "regulator_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:4402",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585420620,
      "name": "regulator_bulk_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585418144,
      "name": "regulator_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:4402",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585290668,
      "name": "regulator_bulk_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585288224,
      "name": "regulator_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:4402",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585609996,
      "name": "regulator_bulk_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585607552,
      "name": "regulator_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int regulator_bulk_get(struct device * dev, int num_consumers, struct regulator_bulk_data * consumers)
```

```json
{
  "name": "regulator_bulk_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "regulator_bulk_get",
      "external": true,
      "loc": "drivers/regulator/core.c:4402",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/devres.c:devm_regulator_bulk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585718124,
      "name": "regulator_bulk_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585715680,
      "name": "regulator_bulk_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
