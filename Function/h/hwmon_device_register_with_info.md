# Function: <code>hwmon_device_register_with_info</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586268832,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:672",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586268832,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586368480,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:677",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586368480,
      "name": "hwmon_device_register_with_info",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586833312,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:690",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586833312,
      "name": "hwmon_device_register_with_info",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587125536,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:690",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587125536,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587304400,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:708",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587304400,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587574752,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:714",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587574752,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587778128,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:728",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587778128,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588625712,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:819",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588625712,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588645712,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:829",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588645712,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588529600,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:829",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588529600,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589203536,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:869",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589203536,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590665088,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:902",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590665088,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592332672,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:903",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592332672,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592759920,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:910",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592759920,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593507968,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:910",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593507968,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500976608,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:728",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500976608,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233491252,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:728",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233491252,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294445888,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:728",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294445888,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277734620,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:728",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277734620,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587409104,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:728",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587409104,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587177312,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:728",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587177312,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587734272,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:728",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587734272,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
```

```json
{
  "name": "hwmon_device_register_with_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587847424,
      "name": "hwmon_device_register_with_info",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:728",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587847424,
      "name": "hwmon_device_register_with_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct device * hwmon_device_register_with_info(struct device * dev, const char * name, void * drvdata, const struct hwmon_chip_info * chip, const struct attribute_group * * extra_groups)
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
