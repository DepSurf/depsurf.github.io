# Function: <code>acpi_data_prop_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int acpi_data_prop_read(struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583607452,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:718",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_dev_prop_read",
        "drivers/acpi/property.c:acpi_node_prop_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583607452,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int acpi_data_prop_read(struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583930528,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:718",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_node_prop_read",
        "drivers/acpi/property.c:acpi_dev_prop_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583930528,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int acpi_data_prop_read(struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584072012,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:790",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_node_prop_read",
        "drivers/acpi/property.c:acpi_dev_prop_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584072012,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int acpi_data_prop_read(struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584135184,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:816",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_dev_prop_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584135184,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584409360,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:823",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_dev_prop_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584409360,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584631792,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:823",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_dev_prop_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584631792,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 687
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
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584731552,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:911",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_dev_prop_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584731552,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 687
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
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584934080,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:929",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_dev_prop_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584934080,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585069888,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:929",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_dev_prop_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585069888,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585775104,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:929",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_dev_prop_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585775104,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585893440,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:934",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_dev_prop_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585893440,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
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
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585770176,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:920",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585770176,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 814
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
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586253088,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:920",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586253088,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 814
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
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587493680,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:931",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587493680,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588760144,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:1075",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588760144,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1018
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
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589048944,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:1063",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589048944,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1059
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
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589354144,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:1130",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589354144,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1061
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
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497474000,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:929",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_dev_prop_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497474000,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
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
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584999376,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:929",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_dev_prop_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584999376,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584914960,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:929",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_dev_prop_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584914960,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585021472,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:929",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_dev_prop_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585021472,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_data_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585127648,
      "name": "acpi_data_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:929",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array",
        "drivers/acpi/property.c:acpi_dev_prop_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585127648,
      "name": "acpi_data_prop_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
<code>struct acpi_device_data * data</code> ➡️ <code>const struct acpi_device_data * data</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_data_prop_read(const struct acpi_device_data * data, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
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
