# Function: <code>tty_port_register_device_attr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584002224,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:88",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584002224,
      "name": "tty_port_register_device_attr",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584333632,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:88",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333632,
      "name": "tty_port_register_device_attr",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584515488,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:88",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584515488,
      "name": "tty_port_register_device_attr",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584595088,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:127",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584595088,
      "name": "tty_port_register_device_attr",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585007223,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:128",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585007120,
      "name": "tty_port_register_device_attr",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585241349,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:128",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585241264,
      "name": "tty_port_register_device_attr",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585360757,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:128",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585360672,
      "name": "tty_port_register_device_attr",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585574389,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:128",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585574304,
      "name": "tty_port_register_device_attr",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585715312,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:129",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585715312,
      "name": "tty_port_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586446117,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:129",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586446176,
      "name": "tty_port_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586560673,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:129",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586560592,
      "name": "tty_port_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586445569,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:130",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586445616,
      "name": "tty_port_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586972001,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:130",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586970192,
      "name": "tty_port_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588268049,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:139",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588266112,
      "name": "tty_port_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589682817,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:160",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589680656,
      "name": "tty_port_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589987425,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:160",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589985264,
      "name": "tty_port_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590325937,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:158",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590323776,
      "name": "tty_port_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498405120,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:129",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498404968,
      "name": "tty_port_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231078976,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:129",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231078876,
      "name": "tty_port_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291589816,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:129",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291589648,
      "name": "tty_port_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276065298,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:129",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276065170,
      "name": "tty_port_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585476336,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:129",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585476336,
      "name": "tty_port_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585346352,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:129",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585346352,
      "name": "tty_port_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585665712,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:129",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585665712,
      "name": "tty_port_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct device * tty_port_register_device_attr(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585773824,
      "name": "tty_port_register_device_attr",
      "external": true,
      "loc": "drivers/tty/tty_port.c:129",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585773824,
      "name": "tty_port_register_device_attr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
