# Function: <code>get_cpu_cacheinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584425099,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:37",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:free_cache_attributes",
        "drivers/base/cacheinfo.c:free_cache_attributes",
        "drivers/base/cacheinfo.c:detect_cache_attributes",
        "drivers/base/cacheinfo.c:detect_cache_attributes",
        "drivers/base/cacheinfo.c:cache_add_dev"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_init_cache_level",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584425312,
      "name": "get_cpu_cacheinfo",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584761589,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:37",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/cacheinfo.c:detect_cache_attributes",
        "drivers/base/cacheinfo.c:detect_cache_attributes",
        "drivers/base/cacheinfo.c:free_cache_attributes",
        "drivers/base/cacheinfo.c:free_cache_attributes"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_init_cache_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584761088,
      "name": "get_cpu_cacheinfo",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584950830,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:40",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:free_cache_attributes",
        "drivers/base/cacheinfo.c:free_cache_attributes"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_init_cache_level",
        "arch/x86/kernel/cpu/intel_rdt.c:get_cache_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584951520,
      "name": "get_cpu_cacheinfo",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585035669,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:40",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_init_cache_level",
        "arch/x86/kernel/cpu/intel_rdt.c:get_cache_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585036368,
      "name": "get_cpu_cacheinfo",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585458533,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:40",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_init_cache_level",
        "arch/x86/kernel/cpu/intel_rdt.c:get_cache_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585459200,
      "name": "get_cpu_cacheinfo",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585702069,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:29",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level",
        "arch/x86/kernel/cpu/intel_rdt.c:get_cache_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585702800,
      "name": "get_cpu_cacheinfo",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585830325,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:29",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level",
        "arch/x86/kernel/cpu/resctrl/core.c:get_cache_id",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585831056,
      "name": "get_cpu_cacheinfo",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586065333,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:29",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/resctrl/core.c:get_cache_id",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586066064,
      "name": "get_cpu_cacheinfo",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586213221,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:29",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/resctrl/core.c:get_cache_id",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586213952,
      "name": "get_cpu_cacheinfo",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586979877,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:29",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586979248,
      "name": "get_cpu_cacheinfo",
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
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587066437,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:29",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587065808,
      "name": "get_cpu_cacheinfo",
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
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586950117,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:29",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586949664,
      "name": "get_cpu_cacheinfo",
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
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587515237,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:29",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587514576,
      "name": "get_cpu_cacheinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588842885,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:29",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_add_dev",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588842144,
      "name": "get_cpu_cacheinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590343089,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:31",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590344480,
      "name": "get_cpu_cacheinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590666914,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:34",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:fetch_cache_info",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:init_cache_level",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590664816,
      "name": "get_cpu_cacheinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591027893,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:34",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:fetch_cache_info",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_remove",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup",
        "drivers/base/cacheinfo.c:cache_shared_cpu_map_setup"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_hygon_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "mm/page_alloc.c:setup_pcp_cacheinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591025248,
      "name": "get_cpu_cacheinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499020368,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:29",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/cacheinfo.c:_populate_cache_leaves",
        "arch/arm64/kernel/cacheinfo.c:_init_cache_level",
        "drivers/acpi/pptt.c:cache_setup_acpi",
        "drivers/acpi/pptt.c:cache_setup_acpi",
        "drivers/acpi/pptt.c:cache_setup_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499020936,
      "name": "get_cpu_cacheinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231582288,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:29",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231582676,
      "name": "get_cpu_cacheinfo",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292182912,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:29",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292183712,
      "name": "get_cpu_cacheinfo",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276387902,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:29",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/cacheinfo.c:_populate_cache_leaves",
        "arch/riscv/kernel/cacheinfo.c:_init_cache_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276388422,
      "name": "get_cpu_cacheinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585973429,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:29",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/resctrl/core.c:get_cache_id",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585974160,
      "name": "get_cpu_cacheinfo",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585822693,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:29",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/resctrl/core.c:get_cache_id",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585823424,
      "name": "get_cpu_cacheinfo",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586163237,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:29",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/resctrl/core.c:get_cache_id",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586163968,
      "name": "get_cpu_cacheinfo",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct cpu_cacheinfo * get_cpu_cacheinfo(unsigned int cpu)
```

```json
{
  "name": "get_cpu_cacheinfo",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586271941,
      "name": "get_cpu_cacheinfo",
      "external": true,
      "loc": "drivers/base/cacheinfo.c:29",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_init_cache_level",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves",
        "arch/x86/kernel/cpu/resctrl/core.c:get_cache_id",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586272672,
      "name": "get_cpu_cacheinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
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
