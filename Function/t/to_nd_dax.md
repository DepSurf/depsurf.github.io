# Function: <code>to_nd_dax</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585108244,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:45",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585108832,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585297300,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:45",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585297888,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585383844,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:45",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585383760,
      "name": "to_nd_dax.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071585383776,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585813044,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:45",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585812960,
      "name": "to_nd_dax.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071585812976,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586059328,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:45",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586059232,
      "name": "to_nd_dax.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586059248,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586200208,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:45",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586200112,
      "name": "to_nd_dax.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586200128,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586436801,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:37",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/claim.c:to_nd_pfn_safe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586437481,
      "name": "to_nd_dax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586437506,
      "name": "to_nd_dax.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071586436720,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586583793,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:37",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/claim.c:to_nd_pfn_safe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586583696,
      "name": "to_nd_dax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586583712,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587369825,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:26",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/claim.c:to_nd_pfn_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587369296,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587430513,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:26",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/claim.c:to_nd_pfn_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587429984,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587312385,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:26",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/claim.c:to_nd_pfn_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587311856,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587879249,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:26",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587878736,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589229409,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:26",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589228784,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590786401,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:26",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590785728,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591127905,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:26",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591127200,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591473585,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:26",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/claim.c:nd_namespace_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591472832,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292742976,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:37",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/claim.c:to_nd_pfn_safe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292742976,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586274273,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:37",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/claim.c:to_nd_pfn_safe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586274176,
      "name": "to_nd_dax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586274192,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586092641,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:37",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/claim.c:to_nd_pfn_safe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release",
        "drivers/dax/pmem/core.c:__dax_pmem_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586092544,
      "name": "to_nd_dax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586092560,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586531761,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:37",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/claim.c:to_nd_pfn_safe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586531664,
      "name": "to_nd_dax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586531680,
      "name": "to_nd_dax",
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
struct nd_dax * to_nd_dax(struct device * dev)
```

```json
{
  "name": "to_nd_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586643489,
      "name": "to_nd_dax",
      "external": true,
      "loc": "drivers/nvdimm/dax_devs.c:37",
      "file": "drivers/nvdimm/dax_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_pmem_forget_poison_check",
        "drivers/nvdimm/region_devs.c:nd_region_advance_seeds",
        "drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe",
        "drivers/nvdimm/claim.c:to_nd_pfn_safe",
        "drivers/nvdimm/dax_devs.c:nd_dax_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586643392,
      "name": "to_nd_dax.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586643408,
      "name": "to_nd_dax",
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct nd_dax * to_nd_dax(struct device * dev)
```
</details>
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
struct nd_dax * to_nd_dax(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct nd_dax * to_nd_dax(struct device * dev)
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
struct nd_dax * to_nd_dax(struct device * dev)
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
