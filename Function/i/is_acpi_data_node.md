# Function: <code>is_acpi_data_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583208643,
      "name": "is_acpi_data_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:410",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_acpi_data_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:410",
      "file": "drivers/acpi/property.c",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583516817,
      "name": "is_acpi_data_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:412",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_acpi_data_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:412",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584756456,
      "name": "is_acpi_data_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:412",
      "file": "drivers/base/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_named_child_node"
      ],
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
  "name": "is_acpi_data_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583657313,
      "name": "is_acpi_data_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:412",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_acpi_data_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:412",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584946680,
      "name": "is_acpi_data_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:412",
      "file": "drivers/base/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_named_child_node"
      ],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583697408,
      "name": "is_acpi_data_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:415",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584134200,
      "name": "is_acpi_data_node",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:415",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode"
      ],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584408360,
      "name": "is_acpi_data_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1306",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584406704,
      "name": "is_acpi_data_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584630808,
      "name": "is_acpi_data_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1314",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584630256,
      "name": "is_acpi_data_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584729925,
      "name": "is_acpi_data_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1355",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584728928,
      "name": "is_acpi_data_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584933372,
      "name": "is_acpi_data_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1381",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584930768,
      "name": "is_acpi_data_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585069180,
      "name": "is_acpi_data_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1381",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585066576,
      "name": "is_acpi_data_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585774694,
      "name": "is_acpi_data_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1429",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585771664,
      "name": "is_acpi_data_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585892998,
      "name": "is_acpi_data_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1444",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585890000,
      "name": "is_acpi_data_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585770022,
      "name": "is_acpi_data_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1423",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585767040,
      "name": "is_acpi_data_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586252934,
      "name": "is_acpi_data_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1418",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586250016,
      "name": "is_acpi_data_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587496149,
      "name": "is_acpi_data_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1455",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587489984,
      "name": "is_acpi_data_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588767445,
      "name": "is_acpi_data_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1626",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod_from_data",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588759696,
      "name": "is_acpi_data_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589054645,
      "name": "is_acpi_data_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1614",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod_from_data",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589048496,
      "name": "is_acpi_data_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589360037,
      "name": "is_acpi_data_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1682",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_parse_string_ref",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod_from_data",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589353696,
      "name": "is_acpi_data_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497473064,
      "name": "is_acpi_data_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1381",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "drivers/irqchip/qcom-irq-combiner.c:combiner_irq_translate",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497470272,
      "name": "is_acpi_data_node",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584998668,
      "name": "is_acpi_data_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1381",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584996064,
      "name": "is_acpi_data_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584914252,
      "name": "is_acpi_data_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1381",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584911648,
      "name": "is_acpi_data_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585020764,
      "name": "is_acpi_data_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1381",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585018160,
      "name": "is_acpi_data_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_acpi_data_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585126940,
      "name": "is_acpi_data_node",
      "external": true,
      "loc": "drivers/acpi/property.c:1381",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:is_acpi_graph_node",
        "drivers/acpi/property.c:acpi_node_get_parent",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_device_data_of_node"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod",
        "drivers/pwm/core.c:devm_fwnode_pwm_get",
        "drivers/pwm/core.c:pwm_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585124336,
      "name": "is_acpi_data_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool is_acpi_data_node(const struct fwnode_handle * fwnode)
```
</details>
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
