# Function: <code>_set_opp_voltage</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```

```json
{
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587052320,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:520",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587052320,
      "name": "_set_opp_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```

```json
{
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587351840,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:527",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587351840,
      "name": "_set_opp_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```

```json
{
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587530976,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:511",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587530976,
      "name": "_set_opp_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```

```json
{
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:580",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587803840,
      "name": "_set_opp_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071587812496,
      "name": "_set_opp_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```

```json
{
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:628",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588008864,
      "name": "_set_opp_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071588017904,
      "name": "_set_opp_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```

```json
{
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:628",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_generic_set_opp_regulator",
        "drivers/opp/core.c:_generic_set_opp_regulator",
        "drivers/opp/core.c:_generic_set_opp_regulator"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588862528,
      "name": "_set_opp_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071588876656,
      "name": "_set_opp_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```

```json
{
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:628",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_generic_set_opp_regulator",
        "drivers/opp/core.c:_generic_set_opp_regulator",
        "drivers/opp/core.c:_generic_set_opp_regulator"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588877728,
      "name": "_set_opp_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071591595696,
      "name": "_set_opp_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```

```json
{
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:707",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588764528,
      "name": "_set_opp_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071591538868,
      "name": "_set_opp_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```

```json
{
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:707",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589455920,
      "name": "_set_opp_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071592652820,
      "name": "_set_opp_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```

```json
{
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:852",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590932720,
      "name": "_set_opp_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071594537426,
      "name": "_set_opp_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592635869,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:792",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_config_regulator_single"
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
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593066461,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:795",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_config_regulator_single"
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
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593817709,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:918",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_config_regulator_single"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```

```json
{
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501263864,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:628",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501263864,
      "name": "_set_opp_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```

```json
{
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233754712,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:628",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233754712,
      "name": "_set_opp_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```

```json
{
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294784656,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:628",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294784656,
      "name": "_set_opp_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```

```json
{
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277941336,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:628",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277941336,
      "name": "_set_opp_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```

```json
{
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:628",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587633856,
      "name": "_set_opp_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071587642896,
      "name": "_set_opp_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```

```json
{
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:628",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587407728,
      "name": "_set_opp_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071587416768,
      "name": "_set_opp_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```

```json
{
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:628",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587965008,
      "name": "_set_opp_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071587974048,
      "name": "_set_opp_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```

```json
{
  "name": "_set_opp_voltage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_set_opp_voltage",
      "external": false,
      "loc": "drivers/opp/core.c:628",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate",
        "drivers/opp/core.c:dev_pm_opp_set_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588080384,
      "name": "_set_opp_voltage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071588089424,
      "name": "_set_opp_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int _set_opp_voltage(struct device * dev, struct regulator * reg, struct dev_pm_opp_supply * supply)
```
</details>
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
