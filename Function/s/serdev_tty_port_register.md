# Function: <code>serdev_tty_port_register</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_tty_port_register",
      "external": false,
      "loc": "include/linux/serdev.h:313",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585178528,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:236",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585178528,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585414368,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:264",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585414368,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585537968,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:264",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585537968,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:264",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585758362,
      "name": "serdev_tty_port_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071585758032,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:264",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585900570,
      "name": "serdev_tty_port_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071585900256,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:264",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586638986,
      "name": "serdev_tty_port_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071586638672,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:264",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591462081,
      "name": "serdev_tty_port_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071586747472,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:264",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591403654,
      "name": "serdev_tty_port_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071586630960,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:264",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592454496,
      "name": "serdev_tty_port_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071587177584,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:264",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594322946,
      "name": "serdev_tty_port_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071588490432,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589927120,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:264",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589927120,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590236480,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:276",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590236480,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
struct device * serdev_tty_port_register(struct tty_port * port, struct device * host, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590577472,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:276",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590577472,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498719016,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:264",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498719016,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231345780,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:264",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231345780,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291871232,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:264",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291871232,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276232574,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:264",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276232574,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:264",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585661562,
      "name": "serdev_tty_port_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071585661248,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_tty_port_register",
      "external": false,
      "loc": "include/linux/serdev.h:318",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:264",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585850970,
      "name": "serdev_tty_port_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071585850656,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```

```json
{
  "name": "serdev_tty_port_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_tty_port_register",
      "external": true,
      "loc": "drivers/tty/serdev/serdev-ttyport.c:264",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_port.c:tty_port_register_device_attr_serdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585958586,
      "name": "serdev_tty_port_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071585958272,
      "name": "serdev_tty_port_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
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
<b>Param reordered. </b>
<code>port, parent, drv, idx</code> ➡️ <code>port, host, parent, drv, idx</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct device * serdev_tty_port_register(struct tty_port * port, struct device * parent, struct tty_driver * drv, int idx)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
