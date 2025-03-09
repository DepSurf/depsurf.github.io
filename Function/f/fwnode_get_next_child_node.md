# Function: <code>fwnode_get_next_child_node</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * fwnode_get_next_child_node(struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585031326,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:949",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_next_child_node"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585029808,
      "name": "fwnode_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585455208,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:992",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_next_child_node"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585452528,
      "name": "fwnode_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585697592,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:1052",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_next_child_node"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585696528,
      "name": "fwnode_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585827848,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:575",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_next_child_node"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826832,
      "name": "fwnode_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586062375,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:599",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_next_child_node"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060544,
      "name": "fwnode_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586210263,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:599",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_next_child_node"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586208432,
      "name": "fwnode_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586975576,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:669",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_next_child_node",
        "drivers/base/property.c:device_get_next_child_node"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586972256,
      "name": "fwnode_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587060936,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:721",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_next_child_node",
        "drivers/base/property.c:device_get_next_child_node"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587057952,
      "name": "fwnode_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586944744,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:721",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_next_child_node",
        "drivers/base/property.c:device_get_next_child_node"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586941744,
      "name": "fwnode_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587509185,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:722",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587506112,
      "name": "fwnode_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588835700,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:722",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:fwnode_get_next_available_child_node"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588833264,
      "name": "fwnode_get_next_child_node",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590336980,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:730",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:fwnode_get_next_available_child_node"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590334160,
      "name": "fwnode_get_next_child_node",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590657076,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:750",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:fwnode_get_next_available_child_node"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590654176,
      "name": "fwnode_get_next_child_node",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591017604,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:814",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:fwnode_get_next_available_child_node"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591014320,
      "name": "fwnode_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499015832,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:599",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_next_child_node"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499012872,
      "name": "fwnode_get_next_child_node",
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
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231576840,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:599",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231576364,
      "name": "fwnode_get_next_child_node",
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
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292174756,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:599",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292174000,
      "name": "fwnode_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276382282,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:599",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276381836,
      "name": "fwnode_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585970471,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:599",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_next_child_node"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585968640,
      "name": "fwnode_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585819735,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:599",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_next_child_node"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585817904,
      "name": "fwnode_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586160279,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:599",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_next_child_node"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586158448,
      "name": "fwnode_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct fwnode_handle * fwnode_get_next_child_node(const struct fwnode_handle * fwnode, struct fwnode_handle * child)
```

```json
{
  "name": "fwnode_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586268983,
      "name": "fwnode_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:599",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_next_child_node"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_child_prop_value",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node",
        "drivers/acpi/property.c:acpi_fwnode_get_named_child_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586267152,
      "name": "fwnode_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct fwnode_handle * fwnode_get_next_child_node(struct fwnode_handle * fwnode, struct fwnode_handle * child)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle * fwnode</code> ➡️ <code>const struct fwnode_handle * fwnode</code>
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
