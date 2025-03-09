# Function: <code>mdio_device_register</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585447744,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:66",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585447744,
      "name": "mdio_device_register",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585650944,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:66",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585650944,
      "name": "mdio_device_register",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585737376,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:77",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585737376,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586171056,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:77",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586171056,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:80",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586423157,
      "name": "mdio_device_register.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071586422800,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586568045,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:80",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586568325,
      "name": "mdio_device_register.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071586567968,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586819458,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:76",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586819733,
      "name": "mdio_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586819376,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586965522,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:76",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586965797,
      "name": "mdio_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586965440,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587788210,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:76",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587788485,
      "name": "mdio_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587788128,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587846354,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:76",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591531750,
      "name": "mdio_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587846272,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587725634,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:76",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591473977,
      "name": "mdio_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587725552,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:76",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592544040,
      "name": "mdio_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588318448,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:76",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594423481,
      "name": "mdio_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071589708368,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591325744,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:78",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591325744,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591687072,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:78",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591687072,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592429936,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:79",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592429936,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499953624,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:76",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499953624,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232495540,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:76",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232495540,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293279856,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:76",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293279856,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277036170,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:76",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277036170,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586722530,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:76",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586722805,
      "name": "mdio_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586722448,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586590834,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:76",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586591109,
      "name": "mdio_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586590752,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586920082,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:76",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586920357,
      "name": "mdio_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586920000,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mdio_device_register(struct mdio_device * mdiodev)
```

```json
{
  "name": "mdio_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587026530,
      "name": "mdio_device_register",
      "external": true,
      "loc": "drivers/net/phy/mdio_device.c:76",
      "file": "drivers/net/phy/mdio_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_create_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587026805,
      "name": "mdio_device_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587026448,
      "name": "mdio_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int mdio_device_register(struct mdio_device * mdiodev)
```
</details>
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
