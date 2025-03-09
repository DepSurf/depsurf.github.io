# Function: <code>fwnode_handle_get</code>

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
void fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585029968,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:1004",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585029968,
      "name": "fwnode_handle_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585452688,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:1050",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585452688,
      "name": "fwnode_handle_get",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585696688,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:1136",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585696688,
      "name": "fwnode_handle_get",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585826992,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:659",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826992,
      "name": "fwnode_handle_get",
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
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586063527,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:683",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060704,
      "name": "fwnode_handle_get",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586211415,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:683",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id"
      ],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586208592,
      "name": "fwnode_handle_get",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586976818,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:762",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_get_nth_parent"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/base/swnode.c:software_node_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586972352,
      "name": "fwnode_handle_get",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587062482,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:814",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_get_nth_parent",
        "drivers/base/property.c:fwnode_get_next_parent_dev"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587058048,
      "name": "fwnode_handle_get",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586946314,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:814",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_get_nth_parent",
        "drivers/base/property.c:fwnode_get_next_parent_dev"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586941840,
      "name": "fwnode_handle_get",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587510753,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:809",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_get_nth_parent",
        "drivers/base/property.c:fwnode_get_next_parent_dev"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_parent",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587506208,
      "name": "fwnode_handle_get",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588837175,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:809",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588833424,
      "name": "fwnode_handle_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590338647,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:817",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590334352,
      "name": "fwnode_handle_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590658737,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:853",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590654368,
      "name": "fwnode_handle_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591019265,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:917",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591014512,
      "name": "fwnode_handle_get",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499017232,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:683",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id"
      ],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499013152,
      "name": "fwnode_handle_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231579948,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:683",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id"
      ],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231576676,
      "name": "fwnode_handle_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292179208,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:683",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id"
      ],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292174496,
      "name": "fwnode_handle_get",
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
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276385130,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:683",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id"
      ],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276382132,
      "name": "fwnode_handle_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585971623,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:683",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id"
      ],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585968800,
      "name": "fwnode_handle_get",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585820887,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:683",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id"
      ],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585818064,
      "name": "fwnode_handle_get",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586161431,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:683",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id"
      ],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586158608,
      "name": "fwnode_handle_get",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * fwnode_handle_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586270135,
      "name": "fwnode_handle_get",
      "external": true,
      "loc": "drivers/base/property.c:683",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id"
      ],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586267312,
      "name": "fwnode_handle_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void fwnode_handle_get(struct fwnode_handle * fwnode)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>struct fwnode_handle *</code>
</li>
</ul>
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
