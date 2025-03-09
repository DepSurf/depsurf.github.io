# Function: <code>property_entries_free</code>

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
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585031552,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/property.c:791",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585031552,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585454160,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/property.c:832",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585454160,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585698368,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/property.c:892",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585698368,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585834370,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/swnode.c:414",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_release"
      ],
      "caller_func": [
        "drivers/base/swnode.c:software_node_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585834176,
      "name": "property_entries_free.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071585834240,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586070944,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/swnode.c:456",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ],
      "caller_func": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586070384,
      "name": "property_entries_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071586070448,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586218544,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/swnode.c:456",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ],
      "caller_func": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586217984,
      "name": "property_entries_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071586218048,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586983837,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/swnode.c:333",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release",
        "drivers/base/swnode.c:software_node_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586984112,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587069406,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/swnode.c:333",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release",
        "drivers/base/swnode.c:software_node_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587069680,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586955858,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/swnode.c:347",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_release",
        "drivers/base/swnode.c:software_node_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586953648,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587521858,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/swnode.c:349",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_release",
        "drivers/base/swnode.c:software_node_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587519728,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588849367,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/swnode.c:349",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_release",
        "drivers/base/swnode.c:software_node_release"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588846784,
      "name": "property_entries_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071588847760,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590353687,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/swnode.c:349",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_release",
        "drivers/base/swnode.c:software_node_release"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590350896,
      "name": "property_entries_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071590350976,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590674631,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/swnode.c:349",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_release",
        "drivers/base/swnode.c:software_node_release"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590671776,
      "name": "property_entries_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071590671856,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591036085,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/swnode.c:349",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/base/swnode.c:software_node_release",
        "drivers/base/swnode.c:software_node_release"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591033136,
      "name": "property_entries_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071591033216,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499027244,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/swnode.c:456",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ],
      "caller_func": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499026720,
      "name": "property_entries_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446603336499026800,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231588936,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/swnode.c:456",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ],
      "caller_func": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231588420,
      "name": "property_entries_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 3231588492,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292194128,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/swnode.c:456",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ],
      "caller_func": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292193232,
      "name": "property_entries_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 13835058055292193360,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276393590,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/swnode.c:456",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ],
      "caller_func": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276393094,
      "name": "property_entries_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446743936276393166,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585978752,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/swnode.c:456",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ],
      "caller_func": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585978192,
      "name": "property_entries_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071585978256,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585828016,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/swnode.c:456",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ],
      "caller_func": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585827456,
      "name": "property_entries_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071585827520,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586168560,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/swnode.c:456",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ],
      "caller_func": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586168000,
      "name": "property_entries_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071586168064,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void property_entries_free(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586277840,
      "name": "property_entries_free",
      "external": true,
      "loc": "drivers/base/swnode.c:456",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ],
      "caller_func": [
        "drivers/base/swnode.c:swnode_register",
        "drivers/base/swnode.c:software_node_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586277280,
      "name": "property_entries_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071586277344,
      "name": "property_entries_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void property_entries_free(const struct property_entry * properties)
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
