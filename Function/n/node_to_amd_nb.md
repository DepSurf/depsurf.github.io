# Function: <code>node_to_amd_nb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579102860,
      "name": "node_to_amd_nb",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:79",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141814,
      "name": "node_to_amd_nb",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:79",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250917,
      "name": "node_to_amd_nb",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:79",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579265256,
      "name": "node_to_amd_nb",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:79",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584215564,
      "name": "node_to_amd_nb",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:79",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579102391,
      "name": "node_to_amd_nb",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:87",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143442,
      "name": "node_to_amd_nb",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:87",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595215808,
      "name": "node_to_amd_nb",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:87",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595219608,
      "name": "node_to_amd_nb",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:87",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584558499,
      "name": "node_to_amd_nb",
      "external": false,
      "loc": "arch/x86/include/asm/amd_nb.h:87",
      "file": "drivers/char/agp/amd64-agp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct amd_northbridge * node_to_amd_nb(int node)
```

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595458834,
      "name": "node_to_amd_nb",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:75",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_df_indirect_read",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262576,
      "name": "node_to_amd_nb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct amd_northbridge * node_to_amd_nb(int node)
```

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596379993,
      "name": "node_to_amd_nb",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:75",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259392,
      "name": "node_to_amd_nb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct amd_northbridge * node_to_amd_nb(int node)
```

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602698166,
      "name": "node_to_amd_nb",
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
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276192,
      "name": "node_to_amd_nb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct amd_northbridge * node_to_amd_nb(int node)
```

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602869638,
      "name": "node_to_amd_nb",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:85",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_df_indirect_read",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287536,
      "name": "node_to_amd_nb",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct amd_northbridge * node_to_amd_nb(int node)
```

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604666700,
      "name": "node_to_amd_nb",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:105",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_df_indirect_read",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579311488,
      "name": "node_to_amd_nb",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct amd_northbridge * node_to_amd_nb(int node)
```

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604765503,
      "name": "node_to_amd_nb",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:106",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_df_indirect_read",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326656,
      "name": "node_to_amd_nb",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct amd_northbridge * node_to_amd_nb(int node)
```

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604791357,
      "name": "node_to_amd_nb",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:112",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_df_indirect_read",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579330704,
      "name": "node_to_amd_nb",
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
struct amd_northbridge * node_to_amd_nb(int node)
```

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609133990,
      "name": "node_to_amd_nb",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:115",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_cache_gart",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_df_indirect_read",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:uli_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360048,
      "name": "node_to_amd_nb",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct amd_northbridge * node_to_amd_nb(int node)
```

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612202563,
      "name": "node_to_amd_nb",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:115",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_cache_gart",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_df_indirect_read",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:uli_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359248,
      "name": "node_to_amd_nb",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct amd_northbridge * node_to_amd_nb(int node)
```

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614343785,
      "name": "node_to_amd_nb",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:115",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_df_indirect_read",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579363648,
      "name": "node_to_amd_nb",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct amd_northbridge * node_to_amd_nb(int node)
```

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615274147,
      "name": "node_to_amd_nb",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:128",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_df_indirect_read",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424208,
      "name": "node_to_amd_nb",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct amd_northbridge * node_to_amd_nb(int node)
```

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617050294,
      "name": "node_to_amd_nb",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:128",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579492704,
      "name": "node_to_amd_nb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct amd_northbridge * node_to_amd_nb(int node)
```

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627693487,
      "name": "node_to_amd_nb",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:141",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587584,
      "name": "node_to_amd_nb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct amd_northbridge * node_to_amd_nb(int node)
```

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619451183,
      "name": "node_to_amd_nb",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:149",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579600080,
      "name": "node_to_amd_nb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct amd_northbridge * node_to_amd_nb(int node)
```

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621747295,
      "name": "node_to_amd_nb",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:165",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/amd_gart_64.c:init_amd_gatt",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd64_cleanup",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629840,
      "name": "node_to_amd_nb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct amd_northbridge * node_to_amd_nb(int node)
```

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604705299,
      "name": "node_to_amd_nb",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:112",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_df_indirect_read",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326608,
      "name": "node_to_amd_nb",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct amd_northbridge * node_to_amd_nb(int node)
```

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604672703,
      "name": "node_to_amd_nb",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:112",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_df_indirect_read",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261056,
      "name": "node_to_amd_nb",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct amd_northbridge * node_to_amd_nb(int node)
```

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604782866,
      "name": "node_to_amd_nb",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:112",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_df_indirect_read",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326528,
      "name": "node_to_amd_nb",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct amd_northbridge * node_to_amd_nb(int node)
```

```json
{
  "name": "node_to_amd_nb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604795498,
      "name": "node_to_amd_nb",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:112",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/kernel/amd_nb.c:amd_set_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_get_subcaches",
        "arch/x86/kernel/amd_nb.c:amd_df_indirect_read",
        "arch/x86/kernel/amd_nb.c:__amd_smn_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/amd_gart_64.c:gart_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/amd64-agp.c:nforce3_agp_init",
        "drivers/char/agp/amd64-agp.c:amd_8151_configure",
        "drivers/char/agp/amd64-agp.c:amd64_fetch_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334816,
      "name": "node_to_amd_nb",
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
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct amd_northbridge * node_to_amd_nb(int node)
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
struct amd_northbridge * node_to_amd_nb(int node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct amd_northbridge * node_to_amd_nb(int node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct amd_northbridge * node_to_amd_nb(int node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct amd_northbridge * node_to_amd_nb(int node)
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
