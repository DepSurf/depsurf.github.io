# Function: <code>is_software_node</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_software_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585835838,
      "name": "is_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:36",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:fwnode_remove_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_parent",
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_property_present",
        "drivers/base/swnode.c:software_node_put",
        "drivers/base/swnode.c:software_node_get"
      ],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585835760,
      "name": "is_software_node",
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
bool is_software_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586072365,
      "name": "is_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:36",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:fwnode_remove_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_parent",
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_property_present",
        "drivers/base/swnode.c:software_node_put",
        "drivers/base/swnode.c:software_node_get",
        "drivers/base/swnode.c:to_software_node"
      ],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586068320,
      "name": "is_software_node",
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
bool is_software_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586220541,
      "name": "is_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:36",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:fwnode_remove_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_parent",
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_property_present",
        "drivers/base/swnode.c:software_node_put",
        "drivers/base/swnode.c:software_node_get",
        "drivers/base/swnode.c:to_software_node"
      ],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586216336,
      "name": "is_software_node",
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
bool is_software_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586986637,
      "name": "is_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:36",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_register_nodes",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_parent",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/base/swnode.c:software_node_get_name",
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_property_present",
        "drivers/base/swnode.c:software_node_put",
        "drivers/base/swnode.c:to_software_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586981376,
      "name": "is_software_node",
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
bool is_software_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587072013,
      "name": "is_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:36",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_unregister_nodes",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_parent",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/base/swnode.c:software_node_get_name",
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_property_present",
        "drivers/base/swnode.c:software_node_put",
        "drivers/base/swnode.c:to_software_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587066864,
      "name": "is_software_node",
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
bool is_software_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586957267,
      "name": "is_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:37",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:device_create_managed_software_node",
        "drivers/base/swnode.c:device_remove_software_node",
        "drivers/base/swnode.c:device_remove_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_unregister_nodes",
        "drivers/base/swnode.c:software_node_graph_parse_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:swnode_graph_find_next_port",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_parent",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/base/swnode.c:software_node_get_name",
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_property_present",
        "drivers/base/swnode.c:software_node_put",
        "drivers/base/swnode.c:to_software_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586950832,
      "name": "is_software_node",
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
bool is_software_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587523678,
      "name": "is_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:39",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:device_create_managed_software_node",
        "drivers/base/swnode.c:device_remove_software_node",
        "drivers/base/swnode.c:device_remove_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_unregister_nodes",
        "drivers/base/swnode.c:software_node_graph_parse_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:swnode_graph_find_next_port",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_parent",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/base/swnode.c:software_node_get_name",
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_property_present",
        "drivers/base/swnode.c:software_node_put",
        "drivers/base/swnode.c:to_software_node"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add",
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587516704,
      "name": "is_software_node",
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
bool is_software_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588853198,
      "name": "is_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:39",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:device_create_managed_software_node",
        "drivers/base/swnode.c:device_remove_software_node",
        "drivers/base/swnode.c:device_remove_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_unregister_nodes",
        "drivers/base/swnode.c:software_node_graph_parse_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:swnode_graph_find_next_port",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/base/swnode.c:software_node_get_name",
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_property_present",
        "drivers/base/swnode.c:software_node_put"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588844368,
      "name": "is_software_node",
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
bool is_software_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590357758,
      "name": "is_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:39",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:device_create_managed_software_node",
        "drivers/base/swnode.c:device_remove_software_node",
        "drivers/base/swnode.c:device_remove_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_unregister_nodes",
        "drivers/base/swnode.c:software_node_graph_parse_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:swnode_graph_find_next_port",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/base/swnode.c:software_node_get_name",
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_property_present",
        "drivers/base/swnode.c:software_node_put"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590348224,
      "name": "is_software_node",
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
bool is_software_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590678254,
      "name": "is_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:39",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:device_create_managed_software_node",
        "drivers/base/swnode.c:device_remove_software_node",
        "drivers/base/swnode.c:device_remove_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_graph_parse_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:swnode_graph_find_next_port",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/base/swnode.c:software_node_get_name",
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_property_present",
        "drivers/base/swnode.c:software_node_put"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590669040,
      "name": "is_software_node",
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
bool is_software_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591039710,
      "name": "is_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:39",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify_remove",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:device_create_managed_software_node",
        "drivers/base/swnode.c:device_remove_software_node",
        "drivers/base/swnode.c:device_remove_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_graph_parse_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:swnode_graph_find_next_port",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/base/swnode.c:software_node_get_name",
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_property_present",
        "drivers/base/swnode.c:software_node_put"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:__irq_domain_create",
        "drivers/gpio/gpiolib.c:gpiod_count",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591030352,
      "name": "is_software_node",
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
bool is_software_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499029824,
      "name": "is_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:36",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:fwnode_remove_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_parent",
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_property_present",
        "drivers/base/swnode.c:software_node_put",
        "drivers/base/swnode.c:software_node_get",
        "drivers/base/swnode.c:to_software_node"
      ],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499024488,
      "name": "is_software_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool is_software_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231590280,
      "name": "is_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:36",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:fwnode_remove_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_parent",
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_property_present",
        "drivers/base/swnode.c:software_node_put",
        "drivers/base/swnode.c:software_node_get",
        "drivers/base/swnode.c:to_software_node"
      ],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231586048,
      "name": "is_software_node",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool is_software_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292197596,
      "name": "is_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:36",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:fwnode_remove_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_parent",
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_property_present",
        "drivers/base/swnode.c:software_node_put",
        "drivers/base/swnode.c:software_node_get",
        "drivers/base/swnode.c:to_software_node"
      ],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292188512,
      "name": "is_software_node",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool is_software_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276395572,
      "name": "is_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:36",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:fwnode_remove_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_parent",
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_property_present",
        "drivers/base/swnode.c:software_node_put",
        "drivers/base/swnode.c:software_node_get",
        "drivers/base/swnode.c:to_software_node"
      ],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276391150,
      "name": "is_software_node",
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
bool is_software_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585980749,
      "name": "is_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:36",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:fwnode_remove_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_parent",
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_property_present",
        "drivers/base/swnode.c:software_node_put",
        "drivers/base/swnode.c:software_node_get",
        "drivers/base/swnode.c:to_software_node"
      ],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585976544,
      "name": "is_software_node",
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
bool is_software_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585830013,
      "name": "is_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:36",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:fwnode_remove_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_parent",
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_property_present",
        "drivers/base/swnode.c:software_node_put",
        "drivers/base/swnode.c:software_node_get",
        "drivers/base/swnode.c:to_software_node"
      ],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585825808,
      "name": "is_software_node",
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
bool is_software_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586170557,
      "name": "is_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:36",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:fwnode_remove_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_parent",
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_property_present",
        "drivers/base/swnode.c:software_node_put",
        "drivers/base/swnode.c:software_node_get",
        "drivers/base/swnode.c:to_software_node"
      ],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586166352,
      "name": "is_software_node",
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
bool is_software_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "is_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586279261,
      "name": "is_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:36",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:software_node_notify",
        "drivers/base/swnode.c:fwnode_remove_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_get_reference_args",
        "drivers/base/swnode.c:software_node_get_named_child_node",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_next_child",
        "drivers/base/swnode.c:software_node_get_parent",
        "drivers/base/swnode.c:software_node_read_string_array",
        "drivers/base/swnode.c:software_node_read_int_array",
        "drivers/base/swnode.c:software_node_property_present",
        "drivers/base/swnode.c:software_node_put",
        "drivers/base/swnode.c:software_node_get",
        "drivers/base/swnode.c:to_software_node"
      ],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586275200,
      "name": "is_software_node",
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
bool is_software_node(const struct fwnode_handle * fwnode)
```
</details>
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
