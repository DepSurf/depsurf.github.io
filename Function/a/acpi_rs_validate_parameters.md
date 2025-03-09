# Function: <code>acpi_rs_validate_parameters</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583710885,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:93",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources"
      ],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583710885,
      "name": "acpi_rs_validate_parameters.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584035405,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:93",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584035304,
      "name": "acpi_rs_validate_parameters.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584177563,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:93",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584177462,
      "name": "acpi_rs_validate_parameters.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584245176,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:93",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584245176,
      "name": "acpi_rs_validate_parameters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584600894,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:93",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584600894,
      "name": "acpi_rs_validate_parameters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584826644,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:57",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584826644,
      "name": "acpi_rs_validate_parameters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584930000,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:57",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584930000,
      "name": "acpi_rs_validate_parameters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585132839,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:57",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585132839,
      "name": "acpi_rs_validate_parameters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585269201,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:57",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585269201,
      "name": "acpi_rs_validate_parameters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585975136,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:57",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585975136,
      "name": "acpi_rs_validate_parameters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586098039,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:57",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586098039,
      "name": "acpi_rs_validate_parameters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585974921,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:57",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585974921,
      "name": "acpi_rs_validate_parameters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586463577,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:57",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586463577,
      "name": "acpi_rs_validate_parameters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587715828,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:57",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_set_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587715828,
      "name": "acpi_rs_validate_parameters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589033008,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:57",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_set_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589033008,
      "name": "acpi_rs_validate_parameters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589324160,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:57",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_set_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589324160,
      "name": "acpi_rs_validate_parameters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589630976,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:57",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_set_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589630976,
      "name": "acpi_rs_validate_parameters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497586368,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:57",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497586368,
      "name": "acpi_rs_validate_parameters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585116495,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:57",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585116495,
      "name": "acpi_rs_validate_parameters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585031807,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:57",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585031807,
      "name": "acpi_rs_validate_parameters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585220785,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:57",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585220785,
      "name": "acpi_rs_validate_parameters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_rs_validate_parameters",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585326945,
      "name": "acpi_rs_validate_parameters",
      "external": false,
      "loc": "drivers/acpi/acpica/rsxface.c:57",
      "file": "drivers/acpi/acpica/rsxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsxface.c:acpi_get_event_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_current_resources",
        "drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585326945,
      "name": "acpi_rs_validate_parameters",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
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
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer * buffer, struct acpi_namespace_node * * return_node)
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
