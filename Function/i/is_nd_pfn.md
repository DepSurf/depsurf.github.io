# Function: <code>is_nd_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584749920,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:41",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/pfn_devs.c:uuid_store",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584749920,
      "name": "is_nd_pfn",
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585107895,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:42",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585103088,
      "name": "is_nd_pfn",
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585296951,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:42",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585292128,
      "name": "is_nd_pfn",
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585383428,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:42",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585378592,
      "name": "is_nd_pfn",
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585812628,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:42",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585807664,
      "name": "is_nd_pfn",
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586058882,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:42",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586053760,
      "name": "is_nd_pfn",
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586199762,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:42",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586193984,
      "name": "is_nd_pfn",
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586435987,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:34",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586431328,
      "name": "is_nd_pfn",
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586583011,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:34",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586577888,
      "name": "is_nd_pfn",
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587368463,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:289",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_detach_and_reset",
        "drivers/nvdimm/claim.c:nd_detach_and_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587363056,
      "name": "is_nd_pfn",
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587429631,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:289",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_detach_and_reset",
        "drivers/nvdimm/claim.c:nd_detach_and_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587424288,
      "name": "is_nd_pfn",
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587311503,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:289",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587306224,
      "name": "is_nd_pfn",
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587878383,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:289",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587873024,
      "name": "is_nd_pfn",
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589228360,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:288",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:pmem_should_map_pages",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589222752,
      "name": "is_nd_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590785256,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:290",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:pmem_should_map_pages",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590778944,
      "name": "is_nd_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591126728,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:290",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:pmem_should_map_pages",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591120448,
      "name": "is_nd_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591472360,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:290",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:pmem_should_map_pages",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591465920,
      "name": "is_nd_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "is_nd_pfn",
      "external": false,
      "loc": "drivers/nvdimm/nd.h:308",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_nd_pfn",
      "external": false,
      "loc": "drivers/nvdimm/nd.h:308",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_nd_pfn",
      "external": false,
      "loc": "drivers/nvdimm/nd.h:308",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_nd_pfn",
      "external": false,
      "loc": "drivers/nvdimm/nd.h:308",
      "file": "drivers/nvdimm/claim.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292735084,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:34",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:to_nd_pfn"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292734912,
      "name": "is_nd_pfn",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "is_nd_pfn",
      "external": false,
      "loc": "drivers/nvdimm/nd.h:308",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_nd_pfn",
      "external": false,
      "loc": "drivers/nvdimm/nd.h:308",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_nd_pfn",
      "external": false,
      "loc": "drivers/nvdimm/nd.h:308",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_nd_pfn",
      "external": false,
      "loc": "drivers/nvdimm/nd.h:308",
      "file": "drivers/nvdimm/claim.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586273491,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:34",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586268368,
      "name": "is_nd_pfn",
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586091859,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:34",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/pmem.c:nd_pmem_probe",
        "drivers/nvdimm/pmem.c:pmem_attach_disk",
        "drivers/nvdimm/pmem.c:pmem_attach_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586086736,
      "name": "is_nd_pfn",
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586530979,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:34",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586525856,
      "name": "is_nd_pfn",
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
bool is_nd_pfn(struct device * dev)
```

```json
{
  "name": "is_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586642707,
      "name": "is_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:34",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:mode_show",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586637584,
      "name": "is_nd_pfn",
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool is_nd_pfn(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool is_nd_pfn(struct device * dev)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool is_nd_pfn(struct device * dev)
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
