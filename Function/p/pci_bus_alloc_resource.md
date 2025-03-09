# Function: <code>pci_bus_alloc_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583233248,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:196",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583233248,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583542112,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:225",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583542112,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583678432,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:225",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583678432,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583718816,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:225",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718816,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583976416,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:225",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583976416,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584170176,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:224",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584170176,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584258080,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:224",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258080,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584451232,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:224",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584451232,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584587824,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:224",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584587824,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585263792,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:224",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:__pci_assign_resource",
        "drivers/pci/setup-res.c:__pci_assign_resource",
        "drivers/pci/setup-res.c:__pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:intel_i9xx_setup_flush",
        "drivers/char/agp/intel-gtt.c:intel_i965_g33_setup_chipset_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585263792,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585421472,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:224",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:__pci_assign_resource",
        "drivers/pci/setup-res.c:__pci_assign_resource",
        "drivers/pci/setup-res.c:__pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:intel_i9xx_setup_flush",
        "drivers/char/agp/intel-gtt.c:intel_i965_g33_setup_chipset_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585421472,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585301984,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:224",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585301984,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585759024,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:224",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585759024,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586943424,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:224",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586943424,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588101344,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:228",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588101344,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588376080,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:250",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588376080,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588671200,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:250",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588671200,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496826472,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:224",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496826472,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230106652,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:224",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230106652,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290898608,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:224",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290898608,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275533250,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:224",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275533250,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584539984,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:224",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584539984,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584468144,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:224",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584468144,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584537984,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:224",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584537984,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int pci_bus_alloc_resource(struct pci_bus * bus, struct resource * res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "pci_bus_alloc_resource",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584645728,
      "name": "pci_bus_alloc_resource",
      "external": true,
      "loc": "drivers/pci/bus.c:224",
      "file": "drivers/pci/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/pci/setup-res.c:_pci_assign_resource",
        "drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584645728,
      "name": "pci_bus_alloc_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
