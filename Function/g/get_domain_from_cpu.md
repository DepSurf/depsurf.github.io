# Function: <code>get_domain_from_cpu</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```

```json
{
  "name": "get_domain_from_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579113815,
      "name": "get_domain_from_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:325",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:rdt_ctrl_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579113728,
      "name": "get_domain_from_cpu",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```

```json
{
  "name": "get_domain_from_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579127207,
      "name": "get_domain_from_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:326",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:rdt_ctrl_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579127120,
      "name": "get_domain_from_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```

```json
{
  "name": "get_domain_from_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579136224,
      "name": "get_domain_from_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:380",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:rdt_ctrl_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579136144,
      "name": "get_domain_from_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```

```json
{
  "name": "get_domain_from_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579197699,
      "name": "get_domain_from_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:413",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579197616,
      "name": "get_domain_from_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```

```json
{
  "name": "get_domain_from_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579210452,
      "name": "get_domain_from_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:405",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210384,
      "name": "get_domain_from_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```

```json
{
  "name": "get_domain_from_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579212708,
      "name": "get_domain_from_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:405",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212640,
      "name": "get_domain_from_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```

```json
{
  "name": "get_domain_from_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579234068,
      "name": "get_domain_from_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:405",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579234000,
      "name": "get_domain_from_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```

```json
{
  "name": "get_domain_from_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579227220,
      "name": "get_domain_from_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:407",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579227152,
      "name": "get_domain_from_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```

```json
{
  "name": "get_domain_from_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579229572,
      "name": "get_domain_from_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:407",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229504,
      "name": "get_domain_from_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```

```json
{
  "name": "get_domain_from_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579268364,
      "name": "get_domain_from_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:336",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268256,
      "name": "get_domain_from_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```

```json
{
  "name": "get_domain_from_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579320780,
      "name": "get_domain_from_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:336",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320656,
      "name": "get_domain_from_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```

```json
{
  "name": "get_domain_from_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579386908,
      "name": "get_domain_from_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:326",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386752,
      "name": "get_domain_from_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```

```json
{
  "name": "get_domain_from_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579396556,
      "name": "get_domain_from_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:351",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396400,
      "name": "get_domain_from_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```

```json
{
  "name": "get_domain_from_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579425004,
      "name": "get_domain_from_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:355",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424848,
      "name": "get_domain_from_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```

```json
{
  "name": "get_domain_from_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579211556,
      "name": "get_domain_from_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:405",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211488,
      "name": "get_domain_from_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```

```json
{
  "name": "get_domain_from_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579146564,
      "name": "get_domain_from_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:405",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579146496,
      "name": "get_domain_from_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```

```json
{
  "name": "get_domain_from_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579212628,
      "name": "get_domain_from_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:405",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212560,
      "name": "get_domain_from_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```

```json
{
  "name": "get_domain_from_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579217908,
      "name": "get_domain_from_cpu",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:405",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_ctrl_update"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579217840,
      "name": "get_domain_from_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```
</details>
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
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct rdt_domain * get_domain_from_cpu(int cpu, struct rdt_resource * r)
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
