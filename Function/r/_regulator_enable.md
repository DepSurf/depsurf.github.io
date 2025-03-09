# Function: <code>_regulator_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583934803,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2090",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_enable"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584269619,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2142",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_enable"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584451475,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2143",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_enable"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584535723,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2153",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_enable"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584945963,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2153",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_enable"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585175862,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2210",
      "file": "drivers/regulator/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_enable"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int _regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2509",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585296528,
      "name": "_regulator_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071585305109,
      "name": "_regulator_enable.cold.68",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
int _regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2464",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585507088,
      "name": "_regulator_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
    },
    {
      "addr": 18446744071585517382,
      "name": "_regulator_enable.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int _regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2472",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585649424,
      "name": "_regulator_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
    },
    {
      "addr": 18446744071585658678,
      "name": "_regulator_enable.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int _regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2503",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586375520,
      "name": "_regulator_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
    },
    {
      "addr": 18446744071586383706,
      "name": "_regulator_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
int _regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2628",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586493232,
      "name": "_regulator_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
    },
    {
      "addr": 18446744071591455839,
      "name": "_regulator_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
int _regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2626",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586376256,
      "name": "_regulator_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
    },
    {
      "addr": 18446744071591397626,
      "name": "_regulator_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
int _regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2726",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586899584,
      "name": "_regulator_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    },
    {
      "addr": 18446744071592442628,
      "name": "_regulator_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
int _regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2773",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588189856,
      "name": "_regulator_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
    },
    {
      "addr": 18446744071594310871,
      "name": "_regulator_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int _regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589591568,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2805",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589591568,
      "name": "_regulator_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
int _regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589893600,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2871",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589893600,
      "name": "_regulator_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
int _regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590231232,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2873",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_bulk_disable",
        "drivers/regulator/core.c:regulator_bulk_enable_async",
        "drivers/regulator/core.c:_regulator_enable",
        "drivers/regulator/core.c:regulator_resolve_supply",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590231232,
      "name": "_regulator_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
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
int _regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498310968,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2472",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498310968,
      "name": "_regulator_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
int _regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230992052,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2472",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230992052,
      "name": "_regulator_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int _regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291482416,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2472",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291482416,
      "name": "_regulator_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
int _regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276001666,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2472",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276001666,
      "name": "_regulator_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int _regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2472",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585410032,
      "name": "_regulator_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
    },
    {
      "addr": 18446744071585419599,
      "name": "_regulator_enable.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int _regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2472",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585280496,
      "name": "_regulator_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
    },
    {
      "addr": 18446744071585289750,
      "name": "_regulator_enable.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int _regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2472",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585599824,
      "name": "_regulator_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
    },
    {
      "addr": 18446744071585609078,
      "name": "_regulator_enable.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int _regulator_enable(struct regulator * regulator)
```

```json
{
  "name": "_regulator_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_regulator_enable",
      "external": false,
      "loc": "drivers/regulator/core.c:2472",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:regulator_enable",
        "drivers/regulator/core.c:_regulator_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585707952,
      "name": "_regulator_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
    },
    {
      "addr": 18446744071585717206,
      "name": "_regulator_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int _regulator_enable(struct regulator * regulator)
```
</details>
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
