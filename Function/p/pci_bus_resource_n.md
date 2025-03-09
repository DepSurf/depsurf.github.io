# Function: <code>pci_bus_resource_n</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583232656,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:64",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/bus.c:pci_bus_clip_resource"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583232656,
      "name": "pci_bus_resource_n.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071583232736,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583542699,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:64",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/setup-bus.c:find_free_bus_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583541504,
      "name": "pci_bus_resource_n.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071583541584,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583679021,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:64",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/setup-bus.c:find_free_bus_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583677824,
      "name": "pci_bus_resource_n.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071583677904,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583719387,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:64",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/setup-bus.c:find_free_bus_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718240,
      "name": "pci_bus_resource_n.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071583718320,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583976982,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:64",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/setup-bus.c:find_free_bus_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583975840,
      "name": "pci_bus_resource_n.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071583975920,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584170728,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:63",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584169600,
      "name": "pci_bus_resource_n.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071584169664,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584258638,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:63",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584257504,
      "name": "pci_bus_resource_n.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071584257568,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584451771,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:63",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584450656,
      "name": "pci_bus_resource_n.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071584450720,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584588365,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:63",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584587248,
      "name": "pci_bus_resource_n.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071584587312,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585264430,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:63",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:assign_fixed_resource_on_bus",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:find_bus_resource_of_type",
        "drivers/pci/setup-bus.c:find_bus_resource_of_type",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/eisa/pci_eisa.c:pci_eisa_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585263168,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585422110,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:63",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:assign_fixed_resource_on_bus",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:find_bus_resource_of_type",
        "drivers/pci/setup-bus.c:find_bus_resource_of_type",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/eisa/pci_eisa.c:pci_eisa_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585420848,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585302625,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:63",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:find_bus_resource_of_type",
        "drivers/pci/setup-bus.c:find_bus_resource_of_type",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585301360,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585759658,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:63",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:find_bus_resource_of_type",
        "drivers/pci/setup-bus.c:find_bus_resource_of_type",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585758320,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586944106,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:63",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:find_bus_resource_of_type",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586942544,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588102123,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:63",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:find_bus_resource_of_type",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588100384,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588377131,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:64",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:find_bus_resource_of_type",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588375120,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588672304,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:64",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_size_bridges",
        "drivers/pci/setup-bus.c:find_bus_resource_of_type",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588670240,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496827164,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:63",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496825832,
      "name": "pci_bus_resource_n.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446603336496825960,
      "name": "pci_bus_resource_n",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230107404,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:63",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_resource"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_resource",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/setup-bus.c:find_free_bus_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230106512,
      "name": "pci_bus_resource_n.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 3230106604,
      "name": "pci_bus_resource_n",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290899420,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:63",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "arch/powerpc/kernel/pci-common.c:pcibios_allocate_bus_resources",
        "arch/powerpc/kernel/pci-common.c:pcibios_setup_bus_self",
        "arch/powerpc/kernel/pci-common.c:pcibios_setup_bus_self",
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:find_free_bus_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290897888,
      "name": "pci_bus_resource_n.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 13835058055290898000,
      "name": "pci_bus_resource_n",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275533766,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:63",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275532708,
      "name": "pci_bus_resource_n.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446743936275532808,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584540523,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:63",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584539408,
      "name": "pci_bus_resource_n.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071584539472,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584468685,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:63",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584467568,
      "name": "pci_bus_resource_n.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071584467632,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584538525,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:63",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584537408,
      "name": "pci_bus_resource_n.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071584537472,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct resource * pci_bus_resource_n(const struct pci_bus * bus, int n)
```

```json
{
  "name": "pci_bus_resource_n",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584646269,
      "name": "pci_bus_resource_n",
      "external": true,
      "loc": "drivers/pci/bus.c:63",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_clip_resource",
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/pci/probe.c:pci_read_bridge_bases",
        "drivers/pci/pci.c:pci_find_parent_resource",
        "drivers/pci/setup-bus.c:pci_bus_dump_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/setup-bus.c:find_free_bus_resource",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/eisa/pci_eisa.c:pci_eisa_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584645152,
      "name": "pci_bus_resource_n.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071584645216,
      "name": "pci_bus_resource_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
