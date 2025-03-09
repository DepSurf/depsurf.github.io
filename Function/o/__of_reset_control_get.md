# Function: <code>__of_reset_control_get</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, int shared)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584285315,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:260",
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
      "addr": 18446744071584285248,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, int shared)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584467027,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:301",
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
      "addr": 18446744071584466960,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584552063,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:332",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__devm_reset_control_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584551488,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584962383,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:432",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__devm_reset_control_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584961760,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585197398,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:462",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__device_reset"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585194768,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585315126,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:462",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__device_reset"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585312304,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585524224,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:601",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585524224,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585665264,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:600",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585665264,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586393831,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:601",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__device_reset"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586390720,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586508967,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:675",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__device_reset"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586505584,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586392086,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:812",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586389744,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586915920,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:813",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586915920,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588208592,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:814",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588208592,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589616432,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:814",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589616432,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589919968,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:814",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589919968,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590258464,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:817",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590258464,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498332728,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:600",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:of_reset_control_array_get",
        "drivers/reset/core.c:__reset_control_get",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498332728,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231025016,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:600",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-meson/platsmp.c:meson_smp_get_core_reset",
        "arch/arm/mach-rockchip/platsmp.c:pmu_set_power_domain",
        "drivers/reset/core.c:of_reset_control_array_get",
        "drivers/reset/core.c:__reset_control_get",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/clocksource/dw_apb_timer_of.c:timer_get_base_and_rate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231025016,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291517504,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:600",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:of_reset_control_array_get",
        "drivers/reset/core.c:__reset_control_get",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291517504,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276020448,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:600",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:of_reset_control_array_get",
        "drivers/reset/core.c:__reset_control_get",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276020448,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585426288,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:600",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585426288,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585296336,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:600",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585296336,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585615664,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:600",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585615664,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, bool shared, bool optional, bool acquired)
```

```json
{
  "name": "__of_reset_control_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585723792,
      "name": "__of_reset_control_get",
      "external": true,
      "loc": "drivers/reset/core.c:600",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585723792,
      "name": "__of_reset_control_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct reset_control * __of_reset_control_get(struct device_node * node, const char * id, int index, int shared)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool optional</code>
</li>
<li>
<b>Param type changed. </b>
<code>int shared</code> ➡️ <code>bool shared</code>
</li>
</ul>
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
