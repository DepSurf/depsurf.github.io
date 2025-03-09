# Function: <code>has_busy_rmid</code>

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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "has_busy_rmid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579124865,
      "name": "has_busy_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:150",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579124512,
      "name": "has_busy_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "has_busy_rmid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579139153,
      "name": "has_busy_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:150",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579138800,
      "name": "has_busy_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "has_busy_rmid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579149121,
      "name": "has_busy_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:150",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148768,
      "name": "has_busy_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "has_busy_rmid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579215553,
      "name": "has_busy_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:147",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579215200,
      "name": "has_busy_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "has_busy_rmid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579228593,
      "name": "has_busy_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:139",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579228240,
      "name": "has_busy_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "has_busy_rmid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579230817,
      "name": "has_busy_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:139",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230464,
      "name": "has_busy_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "has_busy_rmid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579254817,
      "name": "has_busy_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:139",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579254368,
      "name": "has_busy_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "has_busy_rmid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579247683,
      "name": "has_busy_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:202",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579247248,
      "name": "has_busy_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "has_busy_rmid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579249251,
      "name": "has_busy_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:202",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579248896,
      "name": "has_busy_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "has_busy_rmid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579289843,
      "name": "has_busy_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:202",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579289504,
      "name": "has_busy_rmid",
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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "has_busy_rmid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579344177,
      "name": "has_busy_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:202",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343776,
      "name": "has_busy_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "has_busy_rmid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579413921,
      "name": "has_busy_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:291",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413472,
      "name": "has_busy_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "has_busy_rmid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579426369,
      "name": "has_busy_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:308",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425920,
      "name": "has_busy_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "has_busy_rmid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579455953,
      "name": "has_busy_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:308",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579455504,
      "name": "has_busy_rmid",
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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "has_busy_rmid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579229665,
      "name": "has_busy_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:139",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229312,
      "name": "has_busy_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "has_busy_rmid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579164833,
      "name": "has_busy_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:139",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579164480,
      "name": "has_busy_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "has_busy_rmid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579230737,
      "name": "has_busy_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:139",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230384,
      "name": "has_busy_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "has_busy_rmid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579236145,
      "name": "has_busy_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:139",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579235792,
      "name": "has_busy_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
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
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool has_busy_rmid(struct rdt_resource * r, struct rdt_domain * d)
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
