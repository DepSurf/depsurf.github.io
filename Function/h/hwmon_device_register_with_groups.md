# Function: <code>hwmon_device_register_with_groups</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585672368,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:96",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ],
      "caller_func": [
        "drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_groups",
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585672368,
      "name": "hwmon_device_register_with_groups.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    },
    {
      "addr": 18446744071585672640,
      "name": "hwmon_device_register_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586069510,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:96",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ],
      "caller_func": [
        "drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_groups",
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586068928,
      "name": "hwmon_device_register_with_groups.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    },
    {
      "addr": 18446744071586069200,
      "name": "hwmon_device_register_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586269161,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:650",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/hwmon/hwmon.c:devm_hwmon_device_register_with_groups",
        "drivers/hwmon/hwmon.c:hwmon_device_register"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586268800,
      "name": "hwmon_device_register_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586368380,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:652",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586368784,
      "name": "hwmon_device_register_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586833212,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:665",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586833616,
      "name": "hwmon_device_register_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587125429,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:665",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587125824,
      "name": "hwmon_device_register_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587304293,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:683",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587304688,
      "name": "hwmon_device_register_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587574658,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:689",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587575008,
      "name": "hwmon_device_register_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587778034,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:703",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587778384,
      "name": "hwmon_device_register_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588625618,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:794",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588625968,
      "name": "hwmon_device_register_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588645618,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:804",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588645968,
      "name": "hwmon_device_register_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588529506,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:804",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588529856,
      "name": "hwmon_device_register_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589203449,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:844",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589203808,
      "name": "hwmon_device_register_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590664968,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:876",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590665536,
      "name": "hwmon_device_register_with_groups",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592332536,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:877",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592333248,
      "name": "hwmon_device_register_with_groups",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592759784,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:884",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592760496,
      "name": "hwmon_device_register_with_groups",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593507832,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:884",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593508544,
      "name": "hwmon_device_register_with_groups",
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
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500976472,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:703",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500976992,
      "name": "hwmon_device_register_with_groups",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233491156,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:703",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233491536,
      "name": "hwmon_device_register_with_groups",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294445740,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:703",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294446240,
      "name": "hwmon_device_register_with_groups",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277734532,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:703",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277734876,
      "name": "hwmon_device_register_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587409010,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:703",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587409360,
      "name": "hwmon_device_register_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587177218,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:703",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587177568,
      "name": "hwmon_device_register_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587734178,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:703",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587734528,
      "name": "hwmon_device_register_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct device * hwmon_device_register_with_groups(struct device * dev, const char * name, void * drvdata, const struct attribute_group * * groups)
```

```json
{
  "name": "hwmon_device_register_with_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587847330,
      "name": "hwmon_device_register_with_groups",
      "external": true,
      "loc": "drivers/hwmon/hwmon.c:703",
      "file": "drivers/hwmon/hwmon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587847680,
      "name": "hwmon_device_register_with_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
