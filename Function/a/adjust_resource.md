# Function: <code>adjust_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579394352,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:923",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394352,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579406560,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:987",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579406560,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579426864,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:987",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426864,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414688,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:987",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414688,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579442560,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:1005",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579442560,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579457808,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:974",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579457808,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491472,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:968",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491472,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508960,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:982",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508960,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579535008,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:982",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535008,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565728,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:982",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:merge_dpa",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565728,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579547104,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:989",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:merge_dpa",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_free",
        "drivers/dax/bus.c:adjust_dev_dax_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547104,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551728,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:981",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:merge_dpa",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_free",
        "drivers/dax/bus.c:adjust_dev_dax_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551728,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579624304,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:981",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:merge_dpa",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_free",
        "drivers/dax/bus.c:adjust_dev_dax_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624304,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579718848,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:968",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:merge_dpa",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_free",
        "drivers/dax/bus.c:adjust_dev_dax_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718848,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579845776,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:976",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:merge_dpa",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_free",
        "drivers/dax/bus.c:adjust_dev_dax_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579845776,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579896000,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:976",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:merge_dpa",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_free",
        "drivers/dax/bus.c:adjust_dev_dax_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579896000,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579935216,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:1031",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:merge_dpa",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_free",
        "drivers/dax/bus.c:adjust_dev_dax_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579935216,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490681712,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:982",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490681712,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224749676,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:982",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe",
        "drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe",
        "drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe",
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/memory/omap-gpmc.c:gpmc_cs_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224749676,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283503376,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:982",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283503376,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271415100,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:982",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271415100,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508672,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:982",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508672,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579437472,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:982",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579437472,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508592,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:982",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508592,
      "name": "adjust_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int adjust_resource(struct resource * res, resource_size_t start, resource_size_t size)
```

```json
{
  "name": "adjust_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579541456,
      "name": "adjust_resource",
      "external": true,
      "loc": "kernel/resource.c:982",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_update_busn_res_end",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate",
        "drivers/nvdimm/namespace_devs.c:scan_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541456,
      "name": "adjust_resource",
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
