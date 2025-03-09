# Function: <code>resctrl_arch_get_config</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
u32 resctrl_arch_get_config(struct rdt_resource * r, struct rdt_domain * d, u32 closid, enum resctrl_conf_type type)
```

```json
{
  "name": "resctrl_arch_get_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579293680,
      "name": "resctrl_arch_get_config",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:430",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show",
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293680,
      "name": "resctrl_arch_get_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
u32 resctrl_arch_get_config(struct rdt_resource * r, struct rdt_domain * d, u32 closid, enum resctrl_conf_type type)
```

```json
{
  "name": "resctrl_arch_get_config",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579348320,
      "name": "resctrl_arch_get_config",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:430",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show",
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579348320,
      "name": "resctrl_arch_get_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
u32 resctrl_arch_get_config(struct rdt_resource * r, struct rdt_domain * d, u32 closid, enum resctrl_conf_type type)
```

```json
{
  "name": "resctrl_arch_get_config",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579419046,
      "name": "resctrl_arch_get_config",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:458",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show",
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579418656,
      "name": "resctrl_arch_get_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
u32 resctrl_arch_get_config(struct rdt_resource * r, struct rdt_domain * d, u32 closid, enum resctrl_conf_type type)
```

```json
{
  "name": "resctrl_arch_get_config",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579430924,
      "name": "resctrl_arch_get_config",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:450",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show",
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579430544,
      "name": "resctrl_arch_get_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
u32 resctrl_arch_get_config(struct rdt_resource * r, struct rdt_domain * d, u32 closid, enum resctrl_conf_type type)
```

```json
{
  "name": "resctrl_arch_get_config",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579460508,
      "name": "resctrl_arch_get_config",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:452",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show",
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579460128,
      "name": "resctrl_arch_get_config",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
u32 resctrl_arch_get_config(struct rdt_resource * r, struct rdt_domain * d, u32 closid, enum resctrl_conf_type type)
```
</details>
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
