# Function: <code>alloc_iommu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579264352,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:94",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:dma_map_area"
      ]
    },
    {
      "addr": 18446744071584300885,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/dmar.c:1000",
      "file": "drivers/iommu/dmar.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579264352,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579263728,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:93",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:dma_map_area"
      ]
    },
    {
      "addr": 18446744071584647096,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/dmar.c:1012",
      "file": "drivers/iommu/dmar.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579263728,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579279232,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:93",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:dma_map_area"
      ]
    },
    {
      "addr": 18446744071584833144,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/dmar.c:1013",
      "file": "drivers/iommu/dmar.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579279232,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579276000,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:94",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:dma_map_area"
      ]
    },
    {
      "addr": 18446744071584922790,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/dmar.c:1016",
      "file": "drivers/iommu/dmar.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276000,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579294608,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:94",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:dma_map_area"
      ]
    },
    {
      "addr": 18446744071585344118,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/dmar.c:1019",
      "file": "drivers/iommu/dmar.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294608,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579306640,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:95",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:dma_map_area"
      ]
    },
    {
      "addr": 18446744071585586441,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/dmar.c:1019",
      "file": "drivers/iommu/dmar.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579306640,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579331200,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:91",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585710393,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/dmar.c:1019",
      "file": "drivers/iommu/dmar.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331200,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579346464,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:91",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/dmar.c:1008",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346464,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071585937296,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 960
    },
    {
      "addr": 18446744071585944195,
      "name": "alloc_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579350800,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:91",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/dmar.c:1018",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350800,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071586080480,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
    },
    {
      "addr": 18446744071586087354,
      "name": "alloc_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579381216,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:90",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/dmar.c:1023",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381216,
      "name": "alloc_iommu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    },
    {
      "addr": 18446744071586828560,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
    },
    {
      "addr": 18446744071586835863,
      "name": "alloc_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579386656,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:91",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:__dma_map_cont"
      ]
    },
    {
      "addr": 0,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/dmar.c:1046",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386656,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071586885104,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 599
    },
    {
      "addr": 18446744071591477698,
      "name": "alloc_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579390080,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:91",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:__dma_map_cont"
      ]
    },
    {
      "addr": 0,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/dmar.c:1053",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579390080,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071586764432,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
    },
    {
      "addr": 18446744071591418361,
      "name": "alloc_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579452720,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:91",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:__dma_map_cont"
      ]
    },
    {
      "addr": 0,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/dmar.c:1052",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452720,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071587319568,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
    },
    {
      "addr": 18446744071592472526,
      "name": "alloc_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579527056,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:89",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:__dma_map_cont"
      ]
    },
    {
      "addr": 0,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/dmar.c:1048",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579527056,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071588634928,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
    },
    {
      "addr": 18446744071594342342,
      "name": "alloc_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579629728,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:89",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:__dma_map_cont"
      ]
    },
    {
      "addr": 18446744071590104656,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/dmar.c:1027",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629728,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071590104656,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643776,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:89",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:__dma_map_cont"
      ]
    },
    {
      "addr": 18446744071590418320,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/dmar.c:1038",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643776,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071590418320,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 901
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579677632,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:89",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:__dma_map_cont"
      ]
    },
    {
      "addr": 18446744071590762656,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/dmar.c:1038",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579677632,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071590762656,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 948
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Transformation ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579346704,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:91",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/dmar.c:1018",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346704,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071585841600,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
    },
    {
      "addr": 18446744071585848474,
      "name": "alloc_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Transformation ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579278912,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:91",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/dmar.c:1018",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579278912,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071585700640,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
    },
    {
      "addr": 18446744071585707514,
      "name": "alloc_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Transformation ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579346624,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:91",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/dmar.c:1018",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346624,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071586030496,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
    },
    {
      "addr": 18446744071586037370,
      "name": "alloc_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Transformation ❓</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```

```json
{
  "name": "alloc_iommu",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579355072,
      "name": "alloc_iommu",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:91",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_iommu",
      "external": false,
      "loc": "drivers/iommu/dmar.c:1018",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355072,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071586138448,
      "name": "alloc_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
    },
    {
      "addr": 18446744071586145354,
      "name": "alloc_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int alloc_iommu(struct device * dev, int size, long unsigned int align_mask)
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
