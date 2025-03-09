# Function: <code>tty_register_device_attr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583957856,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3278",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583957856,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584291936,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3274",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584291936,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584473936,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3274",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584473936,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584564640,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2821",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_attr",
        "drivers/tty/tty_port.c:tty_port_register_device_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584564640,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584970528,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2928",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584970528,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2949",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585214702,
      "name": "tty_register_device_attr.cold.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585203376,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 469
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3104",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585333646,
      "name": "tty_register_device_attr.cold.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585321648,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3108",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585546386,
      "name": "tty_register_device_attr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585533664,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3104",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device_attr",
        "drivers/tty/tty_port.c:tty_port_register_device_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585687298,
      "name": "tty_register_device_attr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585674544,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3107",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586415810,
      "name": "tty_register_device_attr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071586400352,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3200",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591457621,
      "name": "tty_register_device_attr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071586514592,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3249",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591399359,
      "name": "tty_register_device_attr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071586399520,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3249",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592445768,
      "name": "tty_register_device_attr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071586926208,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3217",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594313853,
      "name": "tty_register_device_attr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071588220288,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589629632,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3215",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589629632,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589933312,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3222",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589933312,
      "name": "tty_register_device_attr",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590271824,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3239",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590271824,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498345592,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3104",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498345592,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231035392,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3104",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231035392,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291542688,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3104",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291542688,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276029778,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3104",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276029778,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3104",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device_attr",
        "drivers/tty/tty_port.c:tty_port_register_device_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585448322,
      "name": "tty_register_device_attr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585435568,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3104",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device_attr",
        "drivers/tty/tty_port.c:tty_port_register_device_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585318354,
      "name": "tty_register_device_attr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585305616,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3104",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device_attr",
        "drivers/tty/tty_port.c:tty_port_register_device_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585637698,
      "name": "tty_register_device_attr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585624944,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
struct device * tty_register_device_attr(struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_io.c:3104",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_register_driver",
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev",
        "drivers/tty/tty_port.c:tty_port_register_device_attr",
        "drivers/tty/tty_port.c:tty_port_register_device_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585746186,
      "name": "tty_register_device_attr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585733552,
      "name": "tty_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
