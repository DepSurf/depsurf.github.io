# Function: <code>__reset_control_get</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__reset_control_get",
      "external": false,
      "loc": "drivers/reset/core.c:214",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__reset_control_get",
      "external": false,
      "loc": "drivers/reset/core.c:255",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584551605,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:396",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:device_reset",
        "drivers/reset/core.c:__devm_reset_control_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584551536,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584961877,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:496",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:device_reset",
        "drivers/reset/core.c:__devm_reset_control_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584961808,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585197381,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:590",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__device_reset"
      ],
      "caller_func": [
        "drivers/reset/core.c:__devm_reset_control_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585196944,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585315109,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:591",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__device_reset"
      ],
      "caller_func": [
        "drivers/reset/core.c:__devm_reset_control_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585313664,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585525931,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:727",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__device_reset",
        "drivers/reset/core.c:__devm_reset_control_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585527800,
      "name": "__reset_control_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071585525872,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 694
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585666912,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:726",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__device_reset",
        "drivers/reset/core.c:__devm_reset_control_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585666912,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586393813,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:727",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__device_reset"
      ],
      "caller_func": [
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586392816,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586508949,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:801",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__device_reset"
      ],
      "caller_func": [
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586507952,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586392032,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:938",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__device_reset",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:__reset_control_bulk_get",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586392032,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586918624,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:938",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__device_reset",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:__reset_control_bulk_get",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586918624,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588211504,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:939",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__device_reset",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:__reset_control_bulk_get",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588211504,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589619616,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:939",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__device_reset",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:__reset_control_bulk_get",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589619616,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589923136,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:939",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__device_reset",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:__reset_control_bulk_get",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589923136,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590261680,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:942",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__device_reset",
        "drivers/reset/core.c:__devm_reset_control_get",
        "drivers/reset/core.c:__reset_control_bulk_get",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590261680,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498333192,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:726",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__device_reset",
        "drivers/reset/core.c:__devm_reset_control_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498333192,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231025472,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:726",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__device_reset",
        "drivers/reset/core.c:__devm_reset_control_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231025472,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291518928,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:726",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__device_reset",
        "drivers/reset/core.c:__devm_reset_control_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291518928,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1824
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276020758,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:726",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__device_reset",
        "drivers/reset/core.c:__devm_reset_control_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276020758,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585427936,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:726",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__device_reset",
        "drivers/reset/core.c:__devm_reset_control_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585427936,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585297984,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:726",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__device_reset",
        "drivers/reset/core.c:__devm_reset_control_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585297984,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585617312,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:726",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__device_reset",
        "drivers/reset/core.c:__devm_reset_control_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585617312,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585725440,
      "name": "__reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:726",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__device_reset",
        "drivers/reset/core.c:__devm_reset_control_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585725440,
      "name": "__reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
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
struct reset_control * __reset_control_get(struct device * dev, const char * id, int index, bool shared, bool optional)
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool acquired</code>
</li>
</ul>
</details>
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
