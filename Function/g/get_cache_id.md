# Function: <code>get_cache_id</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs * id4_regs)
```

```json
{
  "name": "get_cache_id",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579101660,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_cacheinfo.c:931",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119584,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:190",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579119584,
      "name": "get_cache_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void get_cache_id(int cpu, struct _cpuid4_info_regs * id4_regs)
```

```json
{
  "name": "get_cache_id",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579093408,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_cacheinfo.c:932",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111776,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:279",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111776,
      "name": "get_cache_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void get_cache_id(int cpu, struct _cpuid4_info_regs * id4_regs)
```

```json
{
  "name": "get_cache_id",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579104677,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_cacheinfo.c:936",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579125072,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:280",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579125072,
      "name": "get_cache_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void get_cache_id(int cpu, struct _cpuid4_info_regs * id4_regs)
```

```json
{
  "name": "get_cache_id",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579110306,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:978",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579133808,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:334",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579133808,
      "name": "get_cache_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void get_cache_id(int cpu, struct _cpuid4_info_regs * id4_regs)
```

```json
{
  "name": "get_cache_id",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579115970,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1006",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579195136,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:357",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579195136,
      "name": "get_cache_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs * id4_regs)
```

```json
{
  "name": "get_cache_id",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579125301,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1006",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208000,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:349",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579208000,
      "name": "get_cache_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs * id4_regs)
```

```json
{
  "name": "get_cache_id",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579127173,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1006",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210256,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:349",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210256,
      "name": "get_cache_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_cache_id",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579143860,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1006",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579231482,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:349",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_cache_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579140980,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1006",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_cache_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579147069,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1006",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_cache_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579177988,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1006",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_cache_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579224530,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1007",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_cache_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579281906,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1020",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves"
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
  "name": "get_cache_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579288418,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1019",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves"
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
  "name": "get_cache_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579317682,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1013",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:populate_cache_leaves"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs * id4_regs)
```

```json
{
  "name": "get_cache_id",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579127557,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1006",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209104,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:349",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579209104,
      "name": "get_cache_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs * id4_regs)
```

```json
{
  "name": "get_cache_id",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579059221,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1006",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579144064,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:349",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579144064,
      "name": "get_cache_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs * id4_regs)
```

```json
{
  "name": "get_cache_id",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579127109,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1006",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210176,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:349",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210176,
      "name": "get_cache_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs * id4_regs)
```

```json
{
  "name": "get_cache_id",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579132229,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1006",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215456,
      "name": "get_cache_id",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:349",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579215456,
      "name": "get_cache_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void get_cache_id(int cpu, struct _cpuid4_info_regs * id4_regs)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs * id4_regs)
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
void get_cache_id(int cpu, struct _cpuid4_info_regs * id4_regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs * id4_regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs * id4_regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void get_cache_id(int cpu, struct _cpuid4_info_regs * id4_regs)
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
