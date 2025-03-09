# Function: <code>to_nd_btt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584747568,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:47",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe"
      ],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nd_region_notify_driver_action",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584747568,
      "name": "to_nd_btt.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584747600,
      "name": "to_nd_btt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585102866,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:47",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585100784,
      "name": "to_nd_btt.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585100816,
      "name": "to_nd_btt",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585291906,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:47",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585289824,
      "name": "to_nd_btt.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585289856,
      "name": "to_nd_btt",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585378260,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:47",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585375952,
      "name": "to_nd_btt.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071585375968,
      "name": "to_nd_btt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585807332,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:47",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805008,
      "name": "to_nd_btt.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071585805024,
      "name": "to_nd_btt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586053365,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:47",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586051168,
      "name": "to_nd_btt.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586051184,
      "name": "to_nd_btt",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586193589,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:47",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586191376,
      "name": "to_nd_btt.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586191392,
      "name": "to_nd_btt",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586430761,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:39",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586431124,
      "name": "to_nd_btt.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586431149,
      "name": "to_nd_btt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071586428640,
      "name": "to_nd_btt",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586577481,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:39",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586575248,
      "name": "to_nd_btt.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586575264,
      "name": "to_nd_btt",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587362665,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:28",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_detach_and_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587361280,
      "name": "to_nd_btt",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587423913,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:28",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_detach_and_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587422528,
      "name": "to_nd_btt",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587305849,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:28",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
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
      "addr": 18446744071587304464,
      "name": "to_nd_btt",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587872850,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:28",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
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
      "addr": 18446744071587870672,
      "name": "to_nd_btt",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589222571,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:27",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
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
      "addr": 18446744071589220176,
      "name": "to_nd_btt",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590778711,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:27",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
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
      "addr": 18446744071590776128,
      "name": "to_nd_btt",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591120208,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:27",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
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
      "addr": 18446744071591117504,
      "name": "to_nd_btt",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591465680,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:27",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
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
      "addr": 18446744071591462928,
      "name": "to_nd_btt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499467520,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:39",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499464936,
      "name": "to_nd_btt.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446603336499464968,
      "name": "to_nd_btt",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292730960,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:39",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292730960,
      "name": "to_nd_btt",
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
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276688310,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:39",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276685984,
      "name": "to_nd_btt.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446743936276686012,
      "name": "to_nd_btt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586267961,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:39",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586265728,
      "name": "to_nd_btt.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586265744,
      "name": "to_nd_btt",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586086329,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:39",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release",
        "drivers/nvdimm/pmem.c:nd_pmem_remove",
        "drivers/nvdimm/btt.c:nvdimm_namespace_attach_btt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586084096,
      "name": "to_nd_btt.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586084112,
      "name": "to_nd_btt",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586525449,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:39",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586523216,
      "name": "to_nd_btt.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586523232,
      "name": "to_nd_btt",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct nd_btt * to_nd_btt(struct device * dev)
```

```json
{
  "name": "to_nd_btt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586637177,
      "name": "to_nd_btt",
      "external": true,
      "loc": "drivers/nvdimm/btt_devs.c:39",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:is_uuid_busy",
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:size_show",
        "drivers/nvdimm/btt_devs.c:namespace_store",
        "drivers/nvdimm/btt_devs.c:namespace_show",
        "drivers/nvdimm/btt_devs.c:uuid_store",
        "drivers/nvdimm/btt_devs.c:sector_size_store",
        "drivers/nvdimm/btt_devs.c:sector_size_show",
        "drivers/nvdimm/btt_devs.c:nd_btt_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586634944,
      "name": "to_nd_btt.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586634960,
      "name": "to_nd_btt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct nd_btt * to_nd_btt(struct device * dev)
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
