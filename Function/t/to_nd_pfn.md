# Function: <code>to_nd_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584750432,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:47",
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
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/pfn_devs.c:uuid_store",
        "drivers/nvdimm/pfn_devs.c:namespace_store",
        "drivers/nvdimm/pfn_devs.c:namespace_show",
        "drivers/nvdimm/pfn_devs.c:mode_store",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584750432,
      "name": "to_nd_pfn.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584750464,
      "name": "to_nd_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585107895,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:48",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585107360,
      "name": "to_nd_pfn",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585296951,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:48",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585296416,
      "name": "to_nd_pfn",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585383428,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:48",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585380720,
      "name": "to_nd_pfn.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071585380736,
      "name": "to_nd_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585812628,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:48",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585810192,
      "name": "to_nd_pfn.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071585810208,
      "name": "to_nd_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586058878,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:48",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586058016,
      "name": "to_nd_pfn.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586058032,
      "name": "to_nd_pfn",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586199758,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:48",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586198896,
      "name": "to_nd_pfn.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586198912,
      "name": "to_nd_pfn",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586435982,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:40",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586436595,
      "name": "to_nd_pfn.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586436620,
      "name": "to_nd_pfn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071586435120,
      "name": "to_nd_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586583006,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:40",
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
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586582096,
      "name": "to_nd_pfn.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586582112,
      "name": "to_nd_pfn",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587368458,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:29",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587367600,
      "name": "to_nd_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587429626,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:29",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587428768,
      "name": "to_nd_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587311498,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:29",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587310640,
      "name": "to_nd_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587878378,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:29",
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
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587873056,
      "name": "to_nd_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589228356,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:28",
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
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589222800,
      "name": "to_nd_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590785252,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:30",
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
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590779008,
      "name": "to_nd_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591126724,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:30",
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
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591120512,
      "name": "to_nd_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591472356,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:30",
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
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591465984,
      "name": "to_nd_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292735056,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:40",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292735056,
      "name": "to_nd_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586273486,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:40",
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
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586272576,
      "name": "to_nd_pfn.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586272592,
      "name": "to_nd_pfn",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586091854,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:40",
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
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release",
        "drivers/nvdimm/pmem.c:pmem_attach_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586090944,
      "name": "to_nd_pfn.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586090960,
      "name": "to_nd_pfn",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586530974,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:40",
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
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586530064,
      "name": "to_nd_pfn.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586530080,
      "name": "to_nd_pfn",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_pfn * to_nd_pfn(struct device * dev)
```

```json
{
  "name": "to_nd_pfn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586642702,
      "name": "to_nd_pfn",
      "external": true,
      "loc": "drivers/nvdimm/pfn_devs.c:40",
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
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586641792,
      "name": "to_nd_pfn.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586641808,
      "name": "to_nd_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct nd_pfn * to_nd_pfn(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct nd_pfn * to_nd_pfn(struct device * dev)
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
struct nd_pfn * to_nd_pfn(struct device * dev)
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
