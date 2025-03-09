# Function: <code>amd_nb_has_feature</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579104821,
      "name": "amd_nb_has_feature",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:74",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "amd_nb_has_feature",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:74",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "amd_nb_has_feature",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:74",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "amd_nb_has_feature",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:74",
      "file": "drivers/char/agp/amd64-agp.c",
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
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579104309,
      "name": "amd_nb_has_feature",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:82",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "amd_nb_has_feature",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:82",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "amd_nb_has_feature",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:82",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "amd_nb_has_feature",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:82",
      "file": "drivers/char/agp/amd64-agp.c",
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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool amd_nb_has_feature(unsigned int feature)
```

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579262544,
      "name": "amd_nb_has_feature",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:69",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262544,
      "name": "amd_nb_has_feature",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool amd_nb_has_feature(unsigned int feature)
```

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579259360,
      "name": "amd_nb_has_feature",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:69",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259360,
      "name": "amd_nb_has_feature",
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
bool amd_nb_has_feature(unsigned int feature)
```

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579276160,
      "name": "amd_nb_has_feature",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:73",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276160,
      "name": "amd_nb_has_feature",
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
bool amd_nb_has_feature(unsigned int feature)
```

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602869552,
      "name": "amd_nb_has_feature",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:79",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287504,
      "name": "amd_nb_has_feature",
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
bool amd_nb_has_feature(unsigned int feature)
```

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604666614,
      "name": "amd_nb_has_feature",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:99",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579311456,
      "name": "amd_nb_has_feature",
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
bool amd_nb_has_feature(unsigned int feature)
```

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604765422,
      "name": "amd_nb_has_feature",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:100",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326624,
      "name": "amd_nb_has_feature",
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
bool amd_nb_has_feature(unsigned int feature)
```

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604791276,
      "name": "amd_nb_has_feature",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:106",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579330672,
      "name": "amd_nb_has_feature",
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
bool amd_nb_has_feature(unsigned int feature)
```

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579362733,
      "name": "amd_nb_has_feature",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:109",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_cache_gart",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360016,
      "name": "amd_nb_has_feature",
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
bool amd_nb_has_feature(unsigned int feature)
```

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591264246,
      "name": "amd_nb_has_feature",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:109",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_cache_gart",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359216,
      "name": "amd_nb_has_feature",
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
bool amd_nb_has_feature(unsigned int feature)
```

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614343704,
      "name": "amd_nb_has_feature",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:109",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579363616,
      "name": "amd_nb_has_feature",
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
bool amd_nb_has_feature(unsigned int feature)
```

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615274066,
      "name": "amd_nb_has_feature",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:122",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424176,
      "name": "amd_nb_has_feature",
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
bool amd_nb_has_feature(unsigned int feature)
```

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617050202,
      "name": "amd_nb_has_feature",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:122",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579492656,
      "name": "amd_nb_has_feature",
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
bool amd_nb_has_feature(unsigned int feature)
```

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627693282,
      "name": "amd_nb_has_feature",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:135",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587520,
      "name": "amd_nb_has_feature",
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
bool amd_nb_has_feature(unsigned int feature)
```

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619450978,
      "name": "amd_nb_has_feature",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:143",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579600016,
      "name": "amd_nb_has_feature",
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
bool amd_nb_has_feature(unsigned int feature)
```

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621747090,
      "name": "amd_nb_has_feature",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:159",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_l3_attrs",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629776,
      "name": "amd_nb_has_feature",
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
bool amd_nb_has_feature(unsigned int feature)
```

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604705218,
      "name": "amd_nb_has_feature",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:106",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326576,
      "name": "amd_nb_has_feature",
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
bool amd_nb_has_feature(unsigned int feature)
```

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604672622,
      "name": "amd_nb_has_feature",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:106",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261024,
      "name": "amd_nb_has_feature",
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
bool amd_nb_has_feature(unsigned int feature)
```

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604782785,
      "name": "amd_nb_has_feature",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:106",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326496,
      "name": "amd_nb_has_feature",
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
bool amd_nb_has_feature(unsigned int feature)
```

```json
{
  "name": "amd_nb_has_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604795417,
      "name": "amd_nb_has_feature",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:106",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_get_priv_group",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_private_attrs_is_visible",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334784,
      "name": "amd_nb_has_feature",
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
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool amd_nb_has_feature(unsigned int feature)
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
bool amd_nb_has_feature(unsigned int feature)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool amd_nb_has_feature(unsigned int feature)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool amd_nb_has_feature(unsigned int feature)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool amd_nb_has_feature(unsigned int feature)
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
