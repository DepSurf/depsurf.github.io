# Function: <code>fwnode_handle_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584419600,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:879",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584419600,
      "name": "fwnode_handle_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584754960,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:926",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584754960,
      "name": "fwnode_handle_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584945184,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:926",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/iommu/iommu.c:iommu_fwspec_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584945184,
      "name": "fwnode_handle_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585030290,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:1018",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_remote_port_parent",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/iommu/iommu.c:iommu_fwspec_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585030016,
      "name": "fwnode_handle_put",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585453029,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:1067",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_remote_port_parent",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/iommu/iommu.c:iommu_fwspec_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585452736,
      "name": "fwnode_handle_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585697109,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:1153",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_remote_port_parent",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/iommu/iommu.c:iommu_fwspec_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585696736,
      "name": "fwnode_handle_put",
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585827413,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:676",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_remote_port_parent",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/iommu/iommu.c:iommu_fwspec_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585827040,
      "name": "fwnode_handle_put",
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586063379,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:700",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_remote_port_parent",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/iommu/iommu.c:iommu_fwspec_free",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/base/devcon.c:device_connection_find_match",
        "drivers/base/devcon.c:device_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060752,
      "name": "fwnode_handle_put",
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586211267,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:700",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_remote_port_parent",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/iommu/iommu.c:iommu_fwspec_free",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586208640,
      "name": "fwnode_handle_put",
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586976634,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:779",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_remote_node",
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_nth_parent",
        "drivers/base/property.c:fwnode_count_parents"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_remove",
        "lib/vsprintf.c:fwnode_full_name_string",
        "drivers/acpi/property.c:acpi_fwnode_get_name_prefix",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/iommu/iommu.c:iommu_release_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586972400,
      "name": "fwnode_handle_put",
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587063063,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:831",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_connection_find_match",
        "drivers/base/property.c:fwnode_connection_find_match",
        "drivers/base/property.c:fwnode_connection_find_match",
        "drivers/base/property.c:fwnode_connection_find_match",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_remote_node",
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_get_nth_parent",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_get_next_parent_dev",
        "drivers/base/property.c:fwnode_get_next_parent_dev"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_remove",
        "lib/vsprintf.c:fwnode_full_name_string",
        "drivers/acpi/property.c:acpi_fwnode_get_name_prefix",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/iommu/iommu.c:iommu_release_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587058096,
      "name": "fwnode_handle_put",
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586946939,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:831",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_connection_find_match",
        "drivers/base/property.c:fwnode_connection_find_match",
        "drivers/base/property.c:fwnode_connection_find_match",
        "drivers/base/property.c:fwnode_connection_find_match",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_remote_node",
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_get_nth_parent",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_get_next_parent_dev",
        "drivers/base/property.c:fwnode_get_next_parent_dev"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_remove",
        "lib/vsprintf.c:fwnode_full_name_string",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/acpi/property.c:acpi_fwnode_get_name_prefix",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/iommu/iommu.c:iommu_release_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586941888,
      "name": "fwnode_handle_put",
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587511308,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:826",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_connection_find_match",
        "drivers/base/property.c:fwnode_connection_find_match",
        "drivers/base/property.c:fwnode_connection_find_match",
        "drivers/base/property.c:fwnode_connection_find_match",
        "drivers/base/property.c:fwnode_connection_find_match",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_remote_node",
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_get_nth_parent",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_get_next_parent_dev",
        "drivers/base/property.c:fwnode_get_next_parent_dev"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_remove",
        "lib/vsprintf.c:fwnode_full_name_string",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/acpi/property.c:acpi_fwnode_get_name_prefix",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/iommu/iommu.c:iommu_fwspec_free",
        "drivers/iommu/iommu.c:iommu_release_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode",
        "drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587506256,
      "name": "fwnode_handle_put",
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588835306,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:826",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_devcon_matches",
        "drivers/base/property.c:fwnode_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_get_endpoint_count",
        "drivers/base/property.c:fwnode_graph_get_endpoint_count",
        "drivers/base/property.c:fwnode_graph_get_endpoint_count",
        "drivers/base/property.c:fwnode_graph_get_endpoint_count",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_get_next_parent_dev",
        "drivers/base/property.c:fwnode_get_next_parent_dev",
        "drivers/base/property.c:fwnode_get_next_parent_dev",
        "drivers/base/property.c:fwnode_get_next_parent_dev"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_remove",
        "lib/vsprintf.c:fwnode_full_name_string",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/acpi/property.c:acpi_fwnode_get_name_prefix",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/iommu/iommu.c:iommu_fwspec_free",
        "drivers/iommu/iommu.c:iommu_release_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode",
        "drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588834448,
      "name": "fwnode_handle_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590336554,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:834",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_devcon_matches",
        "drivers/base/property.c:fwnode_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_get_endpoint_count",
        "drivers/base/property.c:fwnode_graph_get_endpoint_count",
        "drivers/base/property.c:fwnode_graph_get_endpoint_count",
        "drivers/base/property.c:fwnode_graph_get_endpoint_count",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_graph_get_next_endpoint",
        "drivers/base/property.c:fwnode_graph_get_next_endpoint",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_get_next_parent_dev",
        "drivers/base/property.c:fwnode_get_next_parent_dev",
        "drivers/base/property.c:fwnode_get_next_parent_dev",
        "drivers/base/property.c:fwnode_get_next_parent_dev"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-swnode.c:swnode_gpio_count",
        "drivers/gpio/gpiolib-swnode.c:swnode_find_gpio",
        "drivers/gpio/gpiolib-swnode.c:swnode_find_gpio",
        "drivers/gpio/gpiolib-swnode.c:swnode_find_gpio",
        "drivers/acpi/property.c:acpi_fwnode_get_name_prefix",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/iommu/iommu.c:iommu_fwspec_free",
        "drivers/iommu/iommu.c:iommu_release_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/net/phy/phy_device.c:phy_device_release",
        "drivers/net/phy/mdio_device.c:mdio_device_release",
        "drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode",
        "drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "lib/vsprintf.c:fwnode_full_name_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590335552,
      "name": "fwnode_handle_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590656602,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:870",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_devcon_matches",
        "drivers/base/property.c:fwnode_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_get_endpoint_count",
        "drivers/base/property.c:fwnode_graph_get_endpoint_count",
        "drivers/base/property.c:fwnode_graph_get_endpoint_count",
        "drivers/base/property.c:fwnode_graph_get_endpoint_count",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_graph_get_next_endpoint",
        "drivers/base/property.c:fwnode_graph_get_next_endpoint",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_get_next_parent_dev",
        "drivers/base/property.c:fwnode_get_next_parent_dev",
        "drivers/base/property.c:fwnode_get_next_parent_dev",
        "drivers/base/property.c:fwnode_get_next_parent_dev"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-swnode.c:swnode_gpio_count",
        "drivers/gpio/gpiolib-swnode.c:swnode_find_gpio",
        "drivers/gpio/gpiolib-swnode.c:swnode_find_gpio",
        "drivers/gpio/gpiolib-swnode.c:swnode_find_gpio",
        "drivers/acpi/property.c:acpi_fwnode_get_name_prefix",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/iommu/iommu.c:iommu_fwspec_free",
        "drivers/iommu/iommu.c:iommu_release_device",
        "drivers/iommu/iommu.c:__iommu_probe_device",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/net/phy/phy_device.c:phy_device_release",
        "drivers/net/phy/mdio_device.c:mdio_device_release",
        "drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode",
        "drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "lib/vsprintf.c:fwnode_full_name_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590655600,
      "name": "fwnode_handle_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591017130,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:934",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_devcon_matches",
        "drivers/base/property.c:fwnode_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_devcon_matches",
        "drivers/base/property.c:fwnode_graph_get_endpoint_count",
        "drivers/base/property.c:fwnode_graph_get_endpoint_count",
        "drivers/base/property.c:fwnode_graph_get_endpoint_count",
        "drivers/base/property.c:fwnode_graph_get_endpoint_count",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_graph_get_next_endpoint",
        "drivers/base/property.c:fwnode_graph_get_next_endpoint",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_get_next_parent_dev",
        "drivers/base/property.c:fwnode_get_next_parent_dev",
        "drivers/base/property.c:fwnode_get_next_parent_dev",
        "drivers/base/property.c:fwnode_get_next_parent_dev"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_remove",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-swnode.c:swnode_gpio_count",
        "drivers/gpio/gpiolib-swnode.c:swnode_find_gpio",
        "drivers/gpio/gpiolib-swnode.c:swnode_find_gpio",
        "drivers/gpio/gpiolib-swnode.c:swnode_find_gpio",
        "drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes",
        "drivers/acpi/property.c:acpi_fwnode_get_name_prefix",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/iommu/iommu.c:iommu_fwspec_free",
        "drivers/iommu/iommu.c:iommu_deinit_device",
        "drivers/iommu/iommu.c:iommu_init_device",
        "drivers/iommu/iommu.c:remove_iommu_group",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/gpu/drm/drm_connector.c:drm_connector_cleanup",
        "drivers/gpu/drm/drm_bridge_connector.c:drm_bridge_connector_destroy",
        "drivers/net/phy/phy_device.c:phy_device_release",
        "drivers/net/phy/mdio_bus.c:mdiobus_release",
        "drivers/net/phy/mdio_device.c:mdio_device_release",
        "drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode",
        "drivers/net/phy/sfp-bus.c:sfp_bus_find_fwnode",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_phy_device_register",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent",
        "drivers/power/supply/power_supply_core.c:power_supply_get_battery_info",
        "lib/vsprintf.c:fwnode_full_name_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591015904,
      "name": "fwnode_handle_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499017104,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:700",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_remote_port_parent",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/iommu/iommu.c:iommu_fwspec_free",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499013248,
      "name": "fwnode_handle_put",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231579784,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:700",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_remote_port_parent",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_fwspec_free",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231576744,
      "name": "fwnode_handle_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292179048,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:700",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_remote_port_parent",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_fwspec_free",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292174624,
      "name": "fwnode_handle_put",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276385044,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:700",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_remote_port_parent",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276382202,
      "name": "fwnode_handle_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585971475,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:700",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_remote_port_parent",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/iommu/iommu.c:iommu_fwspec_free",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585968848,
      "name": "fwnode_handle_put",
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585820739,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:700",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_remote_port_parent",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/iommu/iommu.c:iommu_fwspec_free",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585818112,
      "name": "fwnode_handle_put",
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586161283,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:700",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_remote_port_parent",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/iommu/iommu.c:iommu_fwspec_free",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586158656,
      "name": "fwnode_handle_put",
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
void fwnode_handle_put(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_handle_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586269987,
      "name": "fwnode_handle_put",
      "external": true,
      "loc": "drivers/base/property.c:700",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_endpoint_by_id",
        "drivers/base/property.c:fwnode_graph_get_remote_port_parent",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/iommu/iommu.c:iommu_fwspec_free",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match",
        "drivers/base/devcon.c:fwnode_connection_find_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586267360,
      "name": "fwnode_handle_put",
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
