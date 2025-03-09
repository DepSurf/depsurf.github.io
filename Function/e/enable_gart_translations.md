# Function: <code>enable_gart_translations</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579266192,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:568",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266192,
      "name": "enable_gart_translations.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595220372,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:567",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265568,
      "name": "enable_gart_translations.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
void enable_gart_translations()
```

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579281056,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:567",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579281056,
      "name": "enable_gart_translations",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void enable_gart_translations()
```

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579277728,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:568",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277728,
      "name": "enable_gart_translations",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
void enable_gart_translations()
```

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579296336,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:568",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579296336,
      "name": "enable_gart_translations",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
void enable_gart_translations()
```

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579309781,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:560",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579309781,
      "name": "enable_gart_translations",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
void enable_gart_translations()
```

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579334397,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:548",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334397,
      "name": "enable_gart_translations",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
void enable_gart_translations()
```

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579349534,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:542",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579349534,
      "name": "enable_gart_translations",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void enable_gart_translations()
```

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579353870,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:542",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579353870,
      "name": "enable_gart_translations",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void enable_gart_translations()
```

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579384062,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:540",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384062,
      "name": "enable_gart_translations.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071579384262,
      "name": "enable_gart_translations",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void enable_gart_translations()
```

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591265450,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:540",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591265450,
      "name": "enable_gart_translations.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071591265650,
      "name": "enable_gart_translations",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void enable_gart_translations()
```

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591207759,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:540",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591207759,
      "name": "enable_gart_translations",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void enable_gart_translations()
```

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592081318,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:540",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592081318,
      "name": "enable_gart_translations",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void enable_gart_translations()
```

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593848776,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:538",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593848776,
      "name": "enable_gart_translations",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627706993,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:538",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629472,
      "name": "enable_gart_translations.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619464337,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:538",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643520,
      "name": "enable_gart_translations.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621760849,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:538",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579677376,
      "name": "enable_gart_translations.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void enable_gart_translations()
```

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579349774,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:542",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579349774,
      "name": "enable_gart_translations",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void enable_gart_translations()
```

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579281982,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:542",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579281982,
      "name": "enable_gart_translations",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void enable_gart_translations()
```

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579349694,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:542",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579349694,
      "name": "enable_gart_translations",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void enable_gart_translations()
```

```json
{
  "name": "enable_gart_translations",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579358142,
      "name": "enable_gart_translations",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:542",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358142,
      "name": "enable_gart_translations",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void enable_gart_translations()
```
</details>
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
void enable_gart_translations()
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
void enable_gart_translations()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void enable_gart_translations()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void enable_gart_translations()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void enable_gart_translations()
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
