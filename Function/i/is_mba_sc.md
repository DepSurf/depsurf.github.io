# Function: <code>is_mba_sc</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource * r)
```

```json
{
  "name": "is_mba_sc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579136064,
      "name": "is_mba_sc",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:233",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:set_mba_sc",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579136064,
      "name": "is_mba_sc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource * r)
```

```json
{
  "name": "is_mba_sc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579197536,
      "name": "is_mba_sc",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:232",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579197536,
      "name": "is_mba_sc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource * r)
```

```json
{
  "name": "is_mba_sc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579210304,
      "name": "is_mba_sc",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:224",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210304,
      "name": "is_mba_sc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource * r)
```

```json
{
  "name": "is_mba_sc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579212560,
      "name": "is_mba_sc",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:224",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212560,
      "name": "is_mba_sc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource * r)
```

```json
{
  "name": "is_mba_sc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579233920,
      "name": "is_mba_sc",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:224",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init_alloc",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:show_doms",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:show_doms",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579233920,
      "name": "is_mba_sc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource * r)
```

```json
{
  "name": "is_mba_sc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579227072,
      "name": "is_mba_sc",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:225",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init_alloc",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:show_doms",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:show_doms",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579227072,
      "name": "is_mba_sc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource * r)
```

```json
{
  "name": "is_mba_sc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579229424,
      "name": "is_mba_sc",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:225",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229424,
      "name": "is_mba_sc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool is_mba_sc(struct rdt_resource * r)
```

```json
{
  "name": "is_mba_sc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "is_mba_sc",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:155",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_get_config",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592068659,
      "name": "is_mba_sc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071579268112,
      "name": "is_mba_sc",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool is_mba_sc(struct rdt_resource * r)
```

```json
{
  "name": "is_mba_sc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "is_mba_sc",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:155",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_get_config",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593834880,
      "name": "is_mba_sc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071579320480,
      "name": "is_mba_sc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool is_mba_sc(struct rdt_resource * r)
```

```json
{
  "name": "is_mba_sc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "is_mba_sc",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:148",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595962433,
      "name": "is_mba_sc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071579386656,
      "name": "is_mba_sc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool is_mba_sc(struct rdt_resource * r)
```

```json
{
  "name": "is_mba_sc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "is_mba_sc",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:160",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596479974,
      "name": "is_mba_sc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071579396304,
      "name": "is_mba_sc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool is_mba_sc(struct rdt_resource * r)
```

```json
{
  "name": "is_mba_sc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "is_mba_sc",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:161",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597375961,
      "name": "is_mba_sc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071579424752,
      "name": "is_mba_sc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource * r)
```

```json
{
  "name": "is_mba_sc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211408,
      "name": "is_mba_sc",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:224",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211408,
      "name": "is_mba_sc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource * r)
```

```json
{
  "name": "is_mba_sc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579146416,
      "name": "is_mba_sc",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:224",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579146416,
      "name": "is_mba_sc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource * r)
```

```json
{
  "name": "is_mba_sc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579212480,
      "name": "is_mba_sc",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:224",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212480,
      "name": "is_mba_sc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool is_mba_sc(struct rdt_resource * r)
```

```json
{
  "name": "is_mba_sc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579217760,
      "name": "is_mba_sc",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:224",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_show_options",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579217760,
      "name": "is_mba_sc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
bool is_mba_sc(struct rdt_resource * r)
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
bool is_mba_sc(struct rdt_resource * r)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool is_mba_sc(struct rdt_resource * r)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool is_mba_sc(struct rdt_resource * r)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool is_mba_sc(struct rdt_resource * r)
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
