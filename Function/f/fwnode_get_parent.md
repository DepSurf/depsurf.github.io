# Function: <code>fwnode_get_parent</code>

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
struct fwnode_handle * fwnode_get_parent(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585030117,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:938",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585029760,
      "name": "fwnode_get_parent",
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
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585452837,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:980",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585452480,
      "name": "fwnode_get_parent",
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
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585696917,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:1040",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585696480,
      "name": "fwnode_get_parent",
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
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585827221,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:563",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826784,
      "name": "fwnode_get_parent",
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
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586060853,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:587",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060496,
      "name": "fwnode_get_parent",
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
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586208741,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:587",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586208384,
      "name": "fwnode_get_parent",
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
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586975820,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:590",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_nth_parent",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_count_parents"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_name_prefix",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_name_prefix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586972208,
      "name": "fwnode_get_parent",
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
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587061708,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:590",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_get_nth_parent",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_get_next_parent_dev"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_name_prefix",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587057904,
      "name": "fwnode_get_parent",
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
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586945516,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:590",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_get_nth_parent",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_get_next_parent_dev"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_name_prefix",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586941696,
      "name": "fwnode_get_parent",
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
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587509868,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:590",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_get_nth_parent",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_get_next_parent_dev"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_name_prefix",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587506064,
      "name": "fwnode_get_parent",
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
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588836133,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:589",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_get_next_parent_dev",
        "drivers/base/property.c:fwnode_get_next_parent_dev"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_name_prefix",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588833184,
      "name": "fwnode_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590337445,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:597",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_get_next_parent_dev",
        "drivers/base/property.c:fwnode_get_next_parent_dev"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_name_prefix",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590334064,
      "name": "fwnode_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590657541,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:607",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_get_next_parent_dev",
        "drivers/base/property.c:fwnode_get_next_parent_dev"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_name_prefix",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590654080,
      "name": "fwnode_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591018069,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:671",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_remote_port",
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_is_ancestor_of",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_count_parents",
        "drivers/base/property.c:fwnode_get_next_parent_dev",
        "drivers/base/property.c:fwnode_get_next_parent_dev"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_fwnode_get_name_prefix",
        "drivers/acpi/property.c:acpi_fwnode_get_name",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/base/core.c:fw_devlink_create_devlink",
        "drivers/base/swnode.c:software_node_get_name_prefix",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591014224,
      "name": "fwnode_get_parent",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499013424,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:587",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint",
        "drivers/usb/roles/class.c:usb_role_switch_is_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499012792,
      "name": "fwnode_get_parent",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231577096,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:587",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/usb/roles/class.c:usb_role_switch_is_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231576296,
      "name": "fwnode_get_parent",
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
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292175176,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:587",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292173888,
      "name": "fwnode_get_parent",
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
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276382494,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:587",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276381778,
      "name": "fwnode_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585968949,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:587",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585968592,
      "name": "fwnode_get_parent",
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
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585818213,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:587",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585817856,
      "name": "fwnode_get_parent",
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
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586158757,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:587",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586158400,
      "name": "fwnode_get_parent",
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
struct fwnode_handle * fwnode_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586267461,
      "name": "fwnode_get_parent",
      "external": true,
      "loc": "drivers/base/property.c:587",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:fwnode_graph_get_port_parent",
        "drivers/base/property.c:fwnode_get_next_parent"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_graph_parse_endpoint",
        "drivers/acpi/property.c:acpi_graph_get_next_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586267104,
      "name": "fwnode_get_parent",
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
struct fwnode_handle * fwnode_get_parent(struct fwnode_handle * fwnode)
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
