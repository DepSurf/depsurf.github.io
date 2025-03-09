# Function: <code>acpi_node_prop_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int acpi_node_prop_read(struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583608549,
      "name": "acpi_node_prop_read",
      "external": true,
      "loc": "drivers/acpi/property.c:788",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:fwnode_property_read_u64_array",
        "drivers/base/property.c:fwnode_property_read_u64_array",
        "drivers/base/property.c:__fwnode_property_read_string_array",
        "drivers/base/property.c:fwnode_property_read_u8_array",
        "drivers/base/property.c:fwnode_property_read_u8_array",
        "drivers/base/property.c:fwnode_property_read_u16_array",
        "drivers/base/property.c:fwnode_property_read_u16_array",
        "drivers/base/property.c:fwnode_property_read_u32_array",
        "drivers/base/property.c:fwnode_property_read_u32_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583608549,
      "name": "acpi_node_prop_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_node_prop_read(struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583931643,
      "name": "acpi_node_prop_read",
      "external": true,
      "loc": "drivers/acpi/property.c:788",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:__fwnode_property_read_string",
        "drivers/base/property.c:__fwnode_property_read_string_array",
        "drivers/base/property.c:fwnode_property_read_u64_array",
        "drivers/base/property.c:fwnode_property_read_u64_array",
        "drivers/base/property.c:fwnode_property_read_u32_array",
        "drivers/base/property.c:fwnode_property_read_u32_array",
        "drivers/base/property.c:fwnode_property_read_u16_array",
        "drivers/base/property.c:fwnode_property_read_u16_array",
        "drivers/base/property.c:fwnode_property_read_u8_array",
        "drivers/base/property.c:fwnode_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583931643,
      "name": "acpi_node_prop_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_node_prop_read(struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584073127,
      "name": "acpi_node_prop_read",
      "external": true,
      "loc": "drivers/acpi/property.c:860",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:__fwnode_property_read_string",
        "drivers/base/property.c:__fwnode_property_read_string_array",
        "drivers/base/property.c:fwnode_property_read_u64_array",
        "drivers/base/property.c:fwnode_property_read_u64_array",
        "drivers/base/property.c:fwnode_property_read_u32_array",
        "drivers/base/property.c:fwnode_property_read_u32_array",
        "drivers/base/property.c:fwnode_property_read_u16_array",
        "drivers/base/property.c:fwnode_property_read_u16_array",
        "drivers/base/property.c:fwnode_property_read_u8_array",
        "drivers/base/property.c:fwnode_property_read_u8_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584073127,
      "name": "acpi_node_prop_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_node_prop_read(struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584136615,
      "name": "acpi_node_prop_read",
      "external": true,
      "loc": "drivers/acpi/property.c:888",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584138816,
      "name": "acpi_node_prop_read",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_node_prop_read(const struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584410087,
      "name": "acpi_node_prop_read",
      "external": true,
      "loc": "drivers/acpi/property.c:895",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584412224,
      "name": "acpi_node_prop_read",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_node_prop_read(const struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584633301,
      "name": "acpi_node_prop_read",
      "external": true,
      "loc": "drivers/acpi/property.c:895",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584635616,
      "name": "acpi_node_prop_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int acpi_node_prop_read(const struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584732245,
      "name": "acpi_node_prop_read",
      "external": true,
      "loc": "drivers/acpi/property.c:983",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584735328,
      "name": "acpi_node_prop_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int acpi_node_prop_read(const struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584934661,
      "name": "acpi_node_prop_read",
      "external": true,
      "loc": "drivers/acpi/property.c:1001",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584937344,
      "name": "acpi_node_prop_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int acpi_node_prop_read(const struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585070469,
      "name": "acpi_node_prop_read",
      "external": true,
      "loc": "drivers/acpi/property.c:1001",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585073152,
      "name": "acpi_node_prop_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int acpi_node_prop_read(const struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585775733,
      "name": "acpi_node_prop_read",
      "external": true,
      "loc": "drivers/acpi/property.c:1001",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585778304,
      "name": "acpi_node_prop_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int acpi_node_prop_read(const struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585894103,
      "name": "acpi_node_prop_read",
      "external": true,
      "loc": "drivers/acpi/property.c:1016",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585896736,
      "name": "acpi_node_prop_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585771143,
      "name": "acpi_node_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:996",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586254055,
      "name": "acpi_node_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:996",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587496265,
      "name": "acpi_node_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:1007",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
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
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588767737,
      "name": "acpi_node_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:1174",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
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
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589056585,
      "name": "acpi_node_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:1162",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
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
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589360329,
      "name": "acpi_node_prop_read",
      "external": false,
      "loc": "drivers/acpi/property.c:1230",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int acpi_node_prop_read(const struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497474728,
      "name": "acpi_node_prop_read",
      "external": true,
      "loc": "drivers/acpi/property.c:1001",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497477760,
      "name": "acpi_node_prop_read",
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
int acpi_node_prop_read(const struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584999957,
      "name": "acpi_node_prop_read",
      "external": true,
      "loc": "drivers/acpi/property.c:1001",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585002640,
      "name": "acpi_node_prop_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int acpi_node_prop_read(const struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584915541,
      "name": "acpi_node_prop_read",
      "external": true,
      "loc": "drivers/acpi/property.c:1001",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584918224,
      "name": "acpi_node_prop_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int acpi_node_prop_read(const struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585022053,
      "name": "acpi_node_prop_read",
      "external": true,
      "loc": "drivers/acpi/property.c:1001",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585024736,
      "name": "acpi_node_prop_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int acpi_node_prop_read(const struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```

```json
{
  "name": "acpi_node_prop_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585128229,
      "name": "acpi_node_prop_read",
      "external": true,
      "loc": "drivers/acpi/property.c:1001",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_read_string_array",
        "drivers/acpi/property.c:acpi_fwnode_property_read_int_array"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585130912,
      "name": "acpi_node_prop_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int acpi_node_prop_read(const struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
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
int acpi_node_prop_read(const struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_node_prop_read(const struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_node_prop_read(const struct fwnode_handle * fwnode, const char * propname, enum dev_prop_type proptype, void * val, size_t nval)
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
