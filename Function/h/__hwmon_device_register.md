# Function: <code>__hwmon_device_register</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586269273,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:539",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ],
      "caller_func": [
        "drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_groups",
        "drivers/hwmon/hwmon.c:hwmon_device_register",
        "drivers/hwmon/hwmon.c:hwmon_device_register_with_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586266896,
      "name": "__hwmon_device_register.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1767
    },
    {
      "addr": 18446744071586268672,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586366384,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:539",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register",
        "drivers/hwmon/hwmon.c:hwmon_device_register_with_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586366384,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1893
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586831232,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:546",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register",
        "drivers/hwmon/hwmon.c:hwmon_device_register_with_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586831232,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1886
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587123440,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:546",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587123440,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1899
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587302272,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:564",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587302272,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1925
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:564",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587573728,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 837
    },
    {
      "addr": 18446744071587576117,
      "name": "__hwmon_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:580",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587777184,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
    },
    {
      "addr": 18446744071587779474,
      "name": "__hwmon_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:685",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588624912,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
    },
    {
      "addr": 18446744071588626002,
      "name": "__hwmon_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:695",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588644912,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
    },
    {
      "addr": 18446744071591582097,
      "name": "__hwmon_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:695",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588528512,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
    },
    {
      "addr": 18446744071591525148,
      "name": "__hwmon_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:733",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589202432,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 925
    },
    {
      "addr": 18446744071592635448,
      "name": "__hwmon_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:752",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590663744,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1135
    },
    {
      "addr": 18446744071594519156,
      "name": "__hwmon_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592331280,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:753",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592331280,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1147
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592758496,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:757",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592758496,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1169
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593506880,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:757",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593506880,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500975472,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:580",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500975472,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233490148,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:580",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233490148,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 928
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294444336,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:580",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294444336,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1284
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277733686,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:580",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277733686,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 778
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:580",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587408160,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
    },
    {
      "addr": 18446744071587410450,
      "name": "__hwmon_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:580",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587176368,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
    },
    {
      "addr": 18446744071587178658,
      "name": "__hwmon_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:580",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587733328,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
    },
    {
      "addr": 18446744071587735618,
      "name": "__hwmon_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```

```json
{
  "name": "__hwmon_device_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwmon_device_register",
      "external": false,
      "loc": "drivers/hwmon/hwmon.c:580",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587846480,
      "name": "__hwmon_device_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
    },
    {
      "addr": 18446744071587848770,
      "name": "__hwmon_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct device * __hwmon_device_register(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * groups)
```
</details>
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
