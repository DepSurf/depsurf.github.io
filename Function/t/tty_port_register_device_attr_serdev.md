# Function: <code>tty_port_register_device_attr_serdev</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:150",
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
      "addr": 18446744071584595200,
      "name": "tty_port_register_device_attr_serdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585007264,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:151",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585007264,
      "name": "tty_port_register_device_attr_serdev",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585241408,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:151",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585241408,
      "name": "tty_port_register_device_attr_serdev",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585360816,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:151",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585360816,
      "name": "tty_port_register_device_attr_serdev",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585574448,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:151",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585574448,
      "name": "tty_port_register_device_attr_serdev",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585715408,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:152",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585715408,
      "name": "tty_port_register_device_attr_serdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586446245,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:152",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586446352,
      "name": "tty_port_register_device_attr_serdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586560734,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:152",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586560832,
      "name": "tty_port_register_device_attr_serdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586445822,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:153",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586445680,
      "name": "tty_port_register_device_attr_serdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586972062,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:153",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586970256,
      "name": "tty_port_register_device_attr_serdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588268142,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:162",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588266224,
      "name": "tty_port_register_device_attr_serdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589682926,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:183",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589680784,
      "name": "tty_port_register_device_attr_serdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589987534,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:183",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:serial_core_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589985392,
      "name": "tty_port_register_device_attr_serdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * host, struct device * parent, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590326058,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:182",
      "file": "drivers/tty/tty_port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev"
      ],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:serial_core_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590323904,
      "name": "tty_port_register_device_attr_serdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498405176,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:152",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498405176,
      "name": "tty_port_register_device_attr_serdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231079024,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:152",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231079024,
      "name": "tty_port_register_device_attr_serdev",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291589888,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:152",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291589888,
      "name": "tty_port_register_device_attr_serdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276065346,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:152",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276065346,
      "name": "tty_port_register_device_attr_serdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585476432,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:152",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585476432,
      "name": "tty_port_register_device_attr_serdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585346448,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:152",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585346448,
      "name": "tty_port_register_device_attr_serdev",
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
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585665808,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:152",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585665808,
      "name": "tty_port_register_device_attr_serdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```

```json
{
  "name": "tty_port_register_device_attr_serdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585773920,
      "name": "tty_port_register_device_attr_serdev",
      "external": true,
      "loc": "drivers/tty/tty_port.c:152",
      "file": "drivers/tty/tty_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev",
        "drivers/tty/serial/serial_core.c:uart_add_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585773920,
      "name": "tty_port_register_device_attr_serdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct device * tty_port_register_device_attr_serdev(struct tty_port * port, struct tty_driver * driver, unsigned int index, struct device * device, void * drvdata, const struct attribute_group * * attr_grp)
```
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * host</code>
</li>
<li>
<b>Param added. </b>
<code>struct device * parent</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device * device</code>
</li>
<li>
<b>Param reordered. </b>
<code>port, driver, index, device, drvdata, attr_grp</code> ➡️ <code>port, driver, index, host, parent, drvdata, attr_grp</code>
</li>
</ul>
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
