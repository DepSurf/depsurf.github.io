# Function: <code>static_key_enable_cpuslocked</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void static_key_enable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_enable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580713360,
      "name": "static_key_enable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:129",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "kernel/jump_label.c:static_key_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580713360,
      "name": "static_key_enable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void static_key_enable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_enable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580845456,
      "name": "static_key_enable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:130",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/jump_label.c:static_key_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845456,
      "name": "static_key_enable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void static_key_enable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_enable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914256,
      "name": "static_key_enable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:149",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914256,
      "name": "static_key_enable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void static_key_enable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_enable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581012432,
      "name": "static_key_enable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:164",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581012432,
      "name": "static_key_enable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void static_key_enable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_enable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581068928,
      "name": "static_key_enable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:164",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068928,
      "name": "static_key_enable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void static_key_enable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_enable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581248704,
      "name": "static_key_enable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:164",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248704,
      "name": "static_key_enable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void static_key_enable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_enable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581290672,
      "name": "static_key_enable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:164",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_enable",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581290672,
      "name": "static_key_enable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void static_key_enable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_enable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581308336,
      "name": "static_key_enable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:164",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_enable",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581308336,
      "name": "static_key_enable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void static_key_enable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_enable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_enable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:164",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_enable",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592188870,
      "name": "static_key_enable_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581553248,
      "name": "static_key_enable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void static_key_enable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_enable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_enable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:164",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/jump_label.c:static_key_enable",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593963968,
      "name": "static_key_enable_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581904912,
      "name": "static_key_enable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void static_key_enable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_enable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_enable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:192",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/jump_label.c:static_key_enable",
        "mm/vmscan.c:lru_gen_change_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596023614,
      "name": "static_key_enable_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582339152,
      "name": "static_key_enable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void static_key_enable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_enable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_enable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:192",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/jump_label.c:static_key_enable",
        "mm/vmscan.c:lru_gen_change_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596545900,
      "name": "static_key_enable_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582541120,
      "name": "static_key_enable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void static_key_enable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_enable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_enable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:192",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/jump_label.c:static_key_enable",
        "mm/vmscan.c:lru_gen_change_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597449679,
      "name": "static_key_enable_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582710272,
      "name": "static_key_enable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void static_key_enable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_enable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492429328,
      "name": "static_key_enable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:164",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492429328,
      "name": "static_key_enable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void static_key_enable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_enable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285697488,
      "name": "static_key_enable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:164",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285697488,
      "name": "static_key_enable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
    }
  ]
}
```
</details>
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
void static_key_enable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_enable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581037776,
      "name": "static_key_enable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:164",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037776,
      "name": "static_key_enable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void static_key_enable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_enable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580983856,
      "name": "static_key_enable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:164",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580983856,
      "name": "static_key_enable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void static_key_enable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_enable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581028976,
      "name": "static_key_enable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:164",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581028976,
      "name": "static_key_enable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void static_key_enable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_enable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581090400,
      "name": "static_key_enable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:164",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090400,
      "name": "static_key_enable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void static_key_enable_cpuslocked(struct static_key * key)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void static_key_enable_cpuslocked(struct static_key * key)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void static_key_enable_cpuslocked(struct static_key * key)
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
