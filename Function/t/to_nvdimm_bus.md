# Function: <code>to_nvdimm_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584705760,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/core.c:84",
      "file": "drivers/nvdimm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/core.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584705760,
      "name": "to_nvdimm_bus.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584705792,
      "name": "to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585057826,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:262",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/bus.c:nd_bus_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585057728,
      "name": "to_nvdimm_bus.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585057760,
      "name": "to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585241618,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:264",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/bus.c:nd_bus_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585241520,
      "name": "to_nvdimm_bus.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585241552,
      "name": "to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585323529,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:326",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/bus.c:nd_bus_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585323440,
      "name": "to_nvdimm_bus.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071585323456,
      "name": "to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585751497,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:327",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/bus.c:nd_bus_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585751408,
      "name": "to_nvdimm_bus.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071585751424,
      "name": "to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585997477,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:330",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/bus.c:nd_bus_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585997408,
      "name": "to_nvdimm_bus.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071585997424,
      "name": "to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586133781,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:324",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586133648,
      "name": "to_nvdimm_bus.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586133664,
      "name": "to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586369672,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:323",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586375572,
      "name": "to_nvdimm_bus.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586375597,
      "name": "to_nvdimm_bus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071586369536,
      "name": "to_nvdimm_bus",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586517192,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:321",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586517024,
      "name": "to_nvdimm_bus.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586517040,
      "name": "to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587297688,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:326",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587298336,
      "name": "to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587358936,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:326",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_bus_firmware_visible",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_show",
        "drivers/nvdimm/core.c:capability_show",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587359584,
      "name": "to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587241032,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:325",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_bus_firmware_visible",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_show",
        "drivers/nvdimm/core.c:capability_show",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587241600,
      "name": "to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587807560,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:324",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_bus_firmware_visible",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_show",
        "drivers/nvdimm/core.c:capability_show",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587805568,
      "name": "to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589156056,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:315",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_bus_firmware_visible",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_show",
        "drivers/nvdimm/core.c:capability_show",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589154224,
      "name": "to_nvdimm_bus",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590707064,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:315",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_bus_firmware_visible",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_show",
        "drivers/nvdimm/core.c:capability_show",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590704912,
      "name": "to_nvdimm_bus",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591048264,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:315",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_bus_firmware_visible",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_show",
        "drivers/nvdimm/core.c:capability_show",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591046352,
      "name": "to_nvdimm_bus",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591392824,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:315",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_bus_firmware_visible",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_show",
        "drivers/nvdimm/core.c:capability_show",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591390864,
      "name": "to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499403356,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:321",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499401392,
      "name": "to_nvdimm_bus.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446603336499401424,
      "name": "to_nvdimm_bus",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292638176,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:321",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/bus.c:nd_bus_probe",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292638176,
      "name": "to_nvdimm_bus",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276632422,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:321",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276632206,
      "name": "to_nvdimm_bus.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446743936276632234,
      "name": "to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586207672,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:321",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586207504,
      "name": "to_nvdimm_bus.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586207520,
      "name": "to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586026040,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:321",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/acpi/nfit/core.c:nfit_visible",
        "drivers/acpi/nfit/core.c:hw_error_scrub_show",
        "drivers/acpi/nfit/core.c:revision_show",
        "drivers/acpi/nfit/core.c:bus_dsm_mask_show",
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586025872,
      "name": "to_nvdimm_bus.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586025888,
      "name": "to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586465160,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:321",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586464992,
      "name": "to_nvdimm_bus.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586465008,
      "name": "to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586576856,
      "name": "to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:321",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": [
        "drivers/nvdimm/core.c:wait_probe_show",
        "drivers/nvdimm/core.c:provider_show",
        "drivers/nvdimm/core.c:commands_show",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586576688,
      "name": "to_nvdimm_bus.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586576704,
      "name": "to_nvdimm_bus",
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct nvdimm_bus * to_nvdimm_bus(struct device * dev)
```
</details>
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
