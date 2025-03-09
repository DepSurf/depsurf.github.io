# Function: <code>allocate_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579399072,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:693",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:reserve_additional_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399072,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411520,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:724",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:reserve_additional_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411520,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579431824,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:724",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:reserve_additional_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579431824,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579419440,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:724",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:reserve_additional_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579419440,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579447408,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:742",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/balloon.c:reserve_additional_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579447408,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579462304,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:711",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/balloon.c:reserve_additional_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579462304,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579495872,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:705",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:reserve_additional_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579495872,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513840,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:719",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:reserve_additional_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513840,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540000,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:719",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:reserve_additional_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540000,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571680,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:719",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:additional_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571680,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579553088,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:726",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/unpopulated-alloc.c:fill_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579553088,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579557664,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:718",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/unpopulated-alloc.c:fill_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579557664,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579630240,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:718",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/unpopulated-alloc.c:fill_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630240,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579725616,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:705",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/unpopulated-alloc.c:fill_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579725616,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855248,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:706",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/unpopulated-alloc.c:fill_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855248,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579905440,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:706",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/unpopulated-alloc.c:fill_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905440,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579944656,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:761",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:reserve_additional_memory",
        "drivers/xen/unpopulated-alloc.c:fill_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944656,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490686560,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:719",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:reserve_additional_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490686560,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224755276,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:719",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_resource",
        "drivers/memory/omap-gpmc.c:gpmc_cs_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224755276,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283511472,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:719",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283511472,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271420040,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:719",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271420040,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513664,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:719",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513664,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579442464,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:719",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579442464,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513584,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:719",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:reserve_additional_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513584,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int allocate_resource(struct resource * root, struct resource * new, resource_size_t size, resource_size_t min, resource_size_t max, resource_size_t align, resource_size_t (*)(void *, const struct resource *, resource_size_t, resource_size_t) alignf, void * alignf_data)
```

```json
{
  "name": "allocate_resource",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546512,
      "name": "allocate_resource",
      "external": true,
      "loc": "kernel/resource.c:719",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/bus.c:pci_bus_alloc_from_region",
        "drivers/xen/balloon.c:reserve_additional_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546512,
      "name": "allocate_resource",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
