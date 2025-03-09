# Function: <code>acpi_data_get_property</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int acpi_data_get_property(struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583605591,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:352",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_dev_get_property",
        "drivers/acpi/property.c:acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_node_prop_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583605591,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int acpi_data_get_property(struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583928616,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:352",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_node_prop_get",
        "drivers/acpi/property.c:acpi_dev_get_property",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583928616,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int acpi_data_get_property(struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584069811,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:405",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_node_prop_get",
        "drivers/acpi/property.c:acpi_dev_get_property",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584069811,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int acpi_data_get_property(struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584133344,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:421",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584133344,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584406384,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:426",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584406384,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584630304,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:426",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584630304,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584728976,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:477",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584728976,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584931328,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:481",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584931328,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585067136,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:481",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585067136,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585772224,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:481",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585772224,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585890560,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:484",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585890560,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585767584,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:484",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585767584,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586250656,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:484",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586250656,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587490512,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:490",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587490512,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588759776,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:649",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588759776,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589048576,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:649",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589048576,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589353776,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:653",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589353776,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497469776,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:481",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497469776,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584996624,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:481",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584996624,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584912208,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:481",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584912208,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585018720,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:481",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585018720,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_data_get_property",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585124896,
      "name": "acpi_data_get_property",
      "external": false,
      "loc": "drivers/acpi/property.c:481",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_property_present",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:acpi_data_prop_read",
        "drivers/acpi/property.c:__acpi_node_get_property_reference",
        "drivers/acpi/property.c:acpi_init_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585124896,
      "name": "acpi_data_get_property",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_data_get_property(const struct acpi_device_data * data, const char * name, acpi_object_type type, const union acpi_object * * obj)
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
