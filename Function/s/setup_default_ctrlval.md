# Function: <code>setup_default_ctrlval</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void setup_default_ctrlval(struct rdt_resource * r, u32 * dc, u32 * dm)
```

```json
{
  "name": "setup_default_ctrlval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579135427,
      "name": "setup_default_ctrlval",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:442",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:set_mba_sc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579136384,
      "name": "setup_default_ctrlval",
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
void setup_default_ctrlval(struct rdt_resource * r, u32 * dc, u32 * dm)
```

```json
{
  "name": "setup_default_ctrlval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579196892,
      "name": "setup_default_ctrlval",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:475",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579197856,
      "name": "setup_default_ctrlval",
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
void setup_default_ctrlval(struct rdt_resource * r, u32 * dc, u32 * dm)
```

```json
{
  "name": "setup_default_ctrlval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579209745,
      "name": "setup_default_ctrlval",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:467",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210608,
      "name": "setup_default_ctrlval",
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
void setup_default_ctrlval(struct rdt_resource * r, u32 * dc, u32 * dm)
```

```json
{
  "name": "setup_default_ctrlval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579212001,
      "name": "setup_default_ctrlval",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:467",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212864,
      "name": "setup_default_ctrlval",
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
void setup_default_ctrlval(struct rdt_resource * r, u32 * dc, u32 * dm)
```

```json
{
  "name": "setup_default_ctrlval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579233646,
      "name": "setup_default_ctrlval",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:467",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579234224,
      "name": "setup_default_ctrlval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void setup_default_ctrlval(struct rdt_resource * r, u32 * dc, u32 * dm)
```

```json
{
  "name": "setup_default_ctrlval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579226804,
      "name": "setup_default_ctrlval",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:469",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579227376,
      "name": "setup_default_ctrlval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void setup_default_ctrlval(struct rdt_resource * r, u32 * dc, u32 * dm)
```

```json
{
  "name": "setup_default_ctrlval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579228825,
      "name": "setup_default_ctrlval",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:469",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229728,
      "name": "setup_default_ctrlval",
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
void setup_default_ctrlval(struct rdt_resource * r, u32 * dc, u32 * dm)
```

```json
{
  "name": "setup_default_ctrlval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579267452,
      "name": "setup_default_ctrlval",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:404",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268544,
      "name": "setup_default_ctrlval",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void setup_default_ctrlval(struct rdt_resource * r, u32 * dc, u32 * dm)
```

```json
{
  "name": "setup_default_ctrlval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579319672,
      "name": "setup_default_ctrlval",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:404",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579321008,
      "name": "setup_default_ctrlval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
  "name": "setup_default_ctrlval",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579386211,
      "name": "setup_default_ctrlval",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:394",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_default_ctrlval",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579395843,
      "name": "setup_default_ctrlval",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:419",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_default_ctrlval",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579424280,
      "name": "setup_default_ctrlval",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:423",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
void setup_default_ctrlval(struct rdt_resource * r, u32 * dc, u32 * dm)
```

```json
{
  "name": "setup_default_ctrlval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579210849,
      "name": "setup_default_ctrlval",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:467",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211712,
      "name": "setup_default_ctrlval",
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
void setup_default_ctrlval(struct rdt_resource * r, u32 * dc, u32 * dm)
```

```json
{
  "name": "setup_default_ctrlval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579145857,
      "name": "setup_default_ctrlval",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:467",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579146720,
      "name": "setup_default_ctrlval",
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
void setup_default_ctrlval(struct rdt_resource * r, u32 * dc, u32 * dm)
```

```json
{
  "name": "setup_default_ctrlval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579211921,
      "name": "setup_default_ctrlval",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:467",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212784,
      "name": "setup_default_ctrlval",
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
void setup_default_ctrlval(struct rdt_resource * r, u32 * dc, u32 * dm)
```

```json
{
  "name": "setup_default_ctrlval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579217201,
      "name": "setup_default_ctrlval",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:467",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579218064,
      "name": "setup_default_ctrlval",
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void setup_default_ctrlval(struct rdt_resource * r, u32 * dc, u32 * dm)
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
void setup_default_ctrlval(struct rdt_resource * r, u32 * dc, u32 * dm)
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
void setup_default_ctrlval(struct rdt_resource * r, u32 * dc, u32 * dm)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void setup_default_ctrlval(struct rdt_resource * r, u32 * dc, u32 * dm)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void setup_default_ctrlval(struct rdt_resource * r, u32 * dc, u32 * dm)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void setup_default_ctrlval(struct rdt_resource * r, u32 * dc, u32 * dm)
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
