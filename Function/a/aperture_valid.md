# Function: <code>aperture_valid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579358129,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:91",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/aperture_64.c:search_agp_bridge",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
      ]
    },
    {
      "addr": 18446744071584217526,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:91",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358129,
      "name": "aperture_valid",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579365012,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:91",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    },
    {
      "addr": 18446744071584557090,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:91",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579365012,
      "name": "aperture_valid",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579383108,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:91",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    },
    {
      "addr": 18446744071584738994,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:91",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383108,
      "name": "aperture_valid",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579279582,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:91",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    },
    {
      "addr": 18446744071584820608,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:91",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579279582,
      "name": "aperture_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579298237,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    },
    {
      "addr": 18446744071585241536,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579298237,
      "name": "aperture_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579310221,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    },
    {
      "addr": 18446744071585478245,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579310221,
      "name": "aperture_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579334863,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    },
    {
      "addr": 18446744071585601637,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334863,
      "name": "aperture_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579350120,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    },
    {
      "addr": 18446744071585821816,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350120,
      "name": "aperture_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579354456,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    },
    {
      "addr": 18446744071585964472,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579354456,
      "name": "aperture_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579384664,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:read_agp"
      ]
    },
    {
      "addr": 18446744071586705284,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384664,
      "name": "aperture_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591265987,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:read_agp"
      ]
    },
    {
      "addr": 18446744071591466584,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591265987,
      "name": "aperture_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591208292,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:read_agp"
      ]
    },
    {
      "addr": 18446744071591407617,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591208292,
      "name": "aperture_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592081859,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:read_agp"
      ]
    },
    {
      "addr": 18446744071592459186,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592081859,
      "name": "aperture_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593849322,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:91",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:read_agp"
      ]
    },
    {
      "addr": 18446744071594328887,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:91",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/amd64-agp.c:agp_aperture_valid"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593849322,
      "name": "aperture_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627710274,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:91",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:read_agp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589987973,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:91",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/amd64-agp.c:agp_aperture_valid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619467594,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:91",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:read_agp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590297509,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:91",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/amd64-agp.c:agp_aperture_valid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621764106,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:91",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:read_agp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590638821,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:91",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/amd64-agp.c:agp_aperture_valid"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579350360,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    },
    {
      "addr": 18446744071585725448,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350360,
      "name": "aperture_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579282568,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    },
    {
      "addr": 18446744071585584632,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579282568,
      "name": "aperture_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579350280,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    },
    {
      "addr": 18446744071585914488,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350280,
      "name": "aperture_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```

```json
{
  "name": "aperture_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579358728,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    },
    {
      "addr": 18446744071586022472,
      "name": "aperture_valid",
      "external": false,
      "loc": "arch/x86/include/asm/gart.h:92",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358728,
      "name": "aperture_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size)
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
