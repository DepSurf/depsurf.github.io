# Function: <code>acpi_device_data_of_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_device_data * acpi_device_data_of_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583607043,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:401",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_node_prop_get",
        "drivers/acpi/property.c:acpi_node_prop_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583607043,
      "name": "acpi_device_data_of_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
struct acpi_device_data * acpi_device_data_of_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583930118,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:401",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_node_prop_read",
        "drivers/acpi/property.c:acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_node_prop_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583930118,
      "name": "acpi_device_data_of_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
struct acpi_device_data * acpi_device_data_of_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584071544,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:454",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_node_prop_read",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_node_prop_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584071544,
      "name": "acpi_device_data_of_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
struct acpi_device_data * acpi_device_data_of_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584135888,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:470",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584135888,
      "name": "acpi_device_data_of_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
const struct acpi_device_data * acpi_device_data_of_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584406752,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:476",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584406752,
      "name": "acpi_device_data_of_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
const struct acpi_device_data * acpi_device_data_of_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584632480,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:476",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584632480,
      "name": "acpi_device_data_of_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
const struct acpi_device_data * acpi_device_data_of_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584730352,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:532",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584730352,
      "name": "acpi_device_data_of_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
const struct acpi_device_data * acpi_device_data_of_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584930816,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:536",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584930816,
      "name": "acpi_device_data_of_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
const struct acpi_device_data * acpi_device_data_of_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585066624,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:536",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585066624,
      "name": "acpi_device_data_of_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
const struct acpi_device_data * acpi_device_data_of_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585771712,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:536",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585771712,
      "name": "acpi_device_data_of_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
const struct acpi_device_data * acpi_device_data_of_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585890048,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:539",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585890048,
      "name": "acpi_device_data_of_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
const struct acpi_device_data * acpi_device_data_of_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585767088,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:539",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585767088,
      "name": "acpi_device_data_of_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
const struct acpi_device_data * acpi_device_data_of_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586250064,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:539",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586250064,
      "name": "acpi_device_data_of_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587496265,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:545",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588767737,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:704",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589056585,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:704",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589360329,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:708",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:__acpi_node_get_property_reference"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
const struct acpi_device_data * acpi_device_data_of_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497470360,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:536",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497470360,
      "name": "acpi_device_data_of_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
const struct acpi_device_data * acpi_device_data_of_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584996112,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:536",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584996112,
      "name": "acpi_device_data_of_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
const struct acpi_device_data * acpi_device_data_of_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584911696,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:536",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584911696,
      "name": "acpi_device_data_of_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
const struct acpi_device_data * acpi_device_data_of_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585018208,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:536",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585018208,
      "name": "acpi_device_data_of_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
const struct acpi_device_data * acpi_device_data_of_node(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_device_data_of_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585124384,
      "name": "acpi_device_data_of_node",
      "external": false,
      "loc": "drivers/acpi/property.c:536",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585124384,
      "name": "acpi_device_data_of_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle * fwnode</code> ➡️ <code>const struct fwnode_handle * fwnode</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct acpi_device_data *</code> ➡️ <code>const struct acpi_device_data *</code>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
const struct acpi_device_data * acpi_device_data_of_node(const struct fwnode_handle * fwnode)
```
</details>
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
const struct acpi_device_data * acpi_device_data_of_node(const struct fwnode_handle * fwnode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
const struct acpi_device_data * acpi_device_data_of_node(const struct fwnode_handle * fwnode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
const struct acpi_device_data * acpi_device_data_of_node(const struct fwnode_handle * fwnode)
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
