# Function: <code>delay_bw_map</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "delay_bw_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579111667,
      "name": "delay_bw_map",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:297",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:mba_wrmsr"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "delay_bw_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579124963,
      "name": "delay_bw_map",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:298",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:mba_wrmsr"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource * r)
```

```json
{
  "name": "delay_bw_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579134758,
      "name": "delay_bw_map",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:352",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:mba_wrmsr"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579136619,
      "name": "delay_bw_map.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579136096,
      "name": "delay_bw_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
u32 delay_bw_map(long unsigned int bw, struct rdt_resource * r)
```

```json
{
  "name": "delay_bw_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579196102,
      "name": "delay_bw_map",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:384",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579198071,
      "name": "delay_bw_map.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579197568,
      "name": "delay_bw_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
u32 delay_bw_map(long unsigned int bw, struct rdt_resource * r)
```

```json
{
  "name": "delay_bw_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579209014,
      "name": "delay_bw_map",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:376",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210842,
      "name": "delay_bw_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579210336,
      "name": "delay_bw_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
u32 delay_bw_map(long unsigned int bw, struct rdt_resource * r)
```

```json
{
  "name": "delay_bw_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579211270,
      "name": "delay_bw_map",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:376",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213098,
      "name": "delay_bw_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579212592,
      "name": "delay_bw_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
u32 delay_bw_map(long unsigned int bw, struct rdt_resource * r)
```

```json
{
  "name": "delay_bw_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579232630,
      "name": "delay_bw_map",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:376",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579234856,
      "name": "delay_bw_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579233952,
      "name": "delay_bw_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
u32 delay_bw_map(long unsigned int bw, struct rdt_resource * r)
```

```json
{
  "name": "delay_bw_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579225750,
      "name": "delay_bw_map",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:378",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591257231,
      "name": "delay_bw_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579227104,
      "name": "delay_bw_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource * r)
```

```json
{
  "name": "delay_bw_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579228162,
      "name": "delay_bw_map",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:378",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591200572,
      "name": "delay_bw_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071579229456,
      "name": "delay_bw_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource * r)
```

```json
{
  "name": "delay_bw_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579266755,
      "name": "delay_bw_map",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:303",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592068713,
      "name": "delay_bw_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579268176,
      "name": "delay_bw_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource * r)
```

```json
{
  "name": "delay_bw_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579318098,
      "name": "delay_bw_map",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:303",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593834934,
      "name": "delay_bw_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071579320560,
      "name": "delay_bw_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
  "name": "delay_bw_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579384430,
      "name": "delay_bw_map",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:293",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
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
  "name": "delay_bw_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579393834,
      "name": "delay_bw_map",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:318",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
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
  "name": "delay_bw_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579422410,
      "name": "delay_bw_map",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:322",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource * r)
```

```json
{
  "name": "delay_bw_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579210118,
      "name": "delay_bw_map",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:376",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211946,
      "name": "delay_bw_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579211440,
      "name": "delay_bw_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
u32 delay_bw_map(long unsigned int bw, struct rdt_resource * r)
```

```json
{
  "name": "delay_bw_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579145316,
      "name": "delay_bw_map",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:376",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579146805,
      "name": "delay_bw_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579146448,
      "name": "delay_bw_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
u32 delay_bw_map(long unsigned int bw, struct rdt_resource * r)
```

```json
{
  "name": "delay_bw_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579211190,
      "name": "delay_bw_map",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:376",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213018,
      "name": "delay_bw_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579212512,
      "name": "delay_bw_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
u32 delay_bw_map(long unsigned int bw, struct rdt_resource * r)
```

```json
{
  "name": "delay_bw_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579216470,
      "name": "delay_bw_map",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:376",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579218298,
      "name": "delay_bw_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579217792,
      "name": "delay_bw_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource * r)
```
</details>
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
u32 delay_bw_map(long unsigned int bw, struct rdt_resource * r)
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
u32 delay_bw_map(long unsigned int bw, struct rdt_resource * r)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource * r)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource * r)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u32 delay_bw_map(long unsigned int bw, struct rdt_resource * r)
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
