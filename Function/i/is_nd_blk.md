# Function: <code>is_nd_blk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584719147,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:64",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region_devs.c:nd_region_notify_driver_action",
        "drivers/nvdimm/region_devs.c:nd_region_notify_driver_action",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:to_bus_provider",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/namespace_devs.c:is_namespace_uuid_busy",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_blk_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584721312,
      "name": "is_nd_blk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585074084,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:152",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:to_bus_provider",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_blk_seed",
        "drivers/nvdimm/namespace_devs.c:is_namespace_uuid_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585073536,
      "name": "is_nd_blk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585259364,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:167",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:to_bus_provider",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:is_namespace_uuid_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585257792,
      "name": "is_nd_blk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585342489,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:166",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:to_bus_provider",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585340864,
      "name": "is_nd_blk",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585770873,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:166",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:to_bus_provider",
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585769248,
      "name": "is_nd_blk",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586017623,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:166",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_bus_uevent",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586015696,
      "name": "is_nd_blk",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586156471,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:171",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586154416,
      "name": "is_nd_blk",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586391688,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:163",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586389616,
      "name": "is_nd_blk",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586538808,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:163",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586537440,
      "name": "is_nd_blk",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587314205,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:847",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region_devs.c:nd_region_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587322096,
      "name": "is_nd_blk",
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
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587376141,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:847",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region_devs.c:nd_region_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587384032,
      "name": "is_nd_blk",
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
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587257277,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:854",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region",
        "drivers/nvdimm/region_devs.c:nd_region_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587266160,
      "name": "is_nd_blk",
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
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587826815,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:854",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_dev_to_target_node",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587833360,
      "name": "is_nd_blk",
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499427708,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:163",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499426104,
      "name": "is_nd_blk",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292672928,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:163",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292670656,
      "name": "is_nd_blk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276654284,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:163",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276653006,
      "name": "is_nd_blk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586229288,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:163",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586227920,
      "name": "is_nd_blk",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586047656,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:163",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586046288,
      "name": "is_nd_blk",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586486776,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:163",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586485408,
      "name": "is_nd_blk",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nd_blk(struct device * dev)
```

```json
{
  "name": "is_nd_blk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586598520,
      "name": "is_nd_blk",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:163",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa",
        "drivers/nvdimm/region_devs.c:nd_region_available_dpa",
        "drivers/nvdimm/region_devs.c:to_nd_blk_region"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586597152,
      "name": "is_nd_blk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool is_nd_blk(struct device * dev)
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
bool is_nd_blk(struct device * dev)
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
