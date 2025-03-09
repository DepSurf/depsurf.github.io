# Function: <code>_regulator_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct regulator * _regulator_get(struct device * dev, const char * id, bool exclusive, bool allow_dummy)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583942224,
      "name": "_regulator_get",
      "external": false,
      "loc": "drivers/regulator/core.c:1530",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/core.c:regulator_get_optional"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583942224,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
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
struct regulator * _regulator_get(struct device * dev, const char * id, bool exclusive, bool allow_dummy)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584277024,
      "name": "_regulator_get",
      "external": false,
      "loc": "drivers/regulator/core.c:1582",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/core.c:regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584277024,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 633
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
struct regulator * _regulator_get(struct device * dev, const char * id, bool exclusive, bool allow_dummy)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584456496,
      "name": "_regulator_get",
      "external": false,
      "loc": "drivers/regulator/core.c:1583",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584456496,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 633
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584546352,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1589",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584546352,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584956608,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1589",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584956608,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1640",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585190579,
      "name": "_regulator_get.cold.68",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585185792,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1853",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585306968,
      "name": "_regulator_get.cold.75",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585302144,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1835",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585517629,
      "name": "_regulator_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071585507904,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1843",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585659423,
      "name": "_regulator_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071585656592,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1862",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586384002,
      "name": "_regulator_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071586376224,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1919",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591456229,
      "name": "_regulator_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071586494144,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1930",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591398016,
      "name": "_regulator_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071586377168,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:2030",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592443034,
      "name": "_regulator_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071586900608,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:2074",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594311975,
      "name": "_regulator_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071588193312,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 565
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589604136,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:2101",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/core.c:regulator_get"
      ],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/core.c:regulator_get",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589593904,
      "name": "_regulator_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
    },
    {
      "addr": 18446744071596231528,
      "name": "_regulator_get.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589594576,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589907505,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:2165",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/core.c:regulator_get"
      ],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/core.c:regulator_get",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589896928,
      "name": "_regulator_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 882
    },
    {
      "addr": 18446744071596759436,
      "name": "_regulator_get.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589897840,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590245425,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:2167",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/core.c:regulator_get"
      ],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/core.c:regulator_get",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590234672,
      "name": "_regulator_get.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 882
    },
    {
      "addr": 18446744071597667907,
      "name": "_regulator_get.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590235584,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498318848,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1843",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498318848,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231000092,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1843",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231000092,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291493952,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1843",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291493952,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1004
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276008748,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1843",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276008748,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1843",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585420447,
      "name": "_regulator_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071585417584,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1843",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585290495,
      "name": "_regulator_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071585287664,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1843",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585609823,
      "name": "_regulator_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071585606992,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
struct regulator * _regulator_get(struct device * dev, const char * id, enum regulator_get_type get_type)
```

```json
{
  "name": "_regulator_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_get",
      "external": true,
      "loc": "drivers/regulator/core.c:1843",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_get",
        "drivers/regulator/core.c:regulator_get_optional",
        "drivers/regulator/core.c:regulator_get_exclusive",
        "drivers/regulator/devres.c:_devm_regulator_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585717951,
      "name": "_regulator_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071585715120,
      "name": "_regulator_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum regulator_get_type get_type</code>
</li>
<li>
<b>Param removed. </b>
<code>bool exclusive</code>
</li>
<li>
<b>Param removed. </b>
<code>bool allow_dummy</code>
</li>
</ul>
</details>
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
