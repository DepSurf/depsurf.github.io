# Function: <code>static_key_disable_cpuslocked</code>

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
void static_key_disable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_disable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580713536,
      "name": "static_key_disable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:159",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "kernel/jump_label.c:static_key_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580713536,
      "name": "static_key_disable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void static_key_disable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_disable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580845632,
      "name": "static_key_disable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:160",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "kernel/jump_label.c:static_key_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845632,
      "name": "static_key_disable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void static_key_disable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_disable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914432,
      "name": "static_key_disable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:180",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914432,
      "name": "static_key_disable_cpuslocked",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void static_key_disable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_disable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581012608,
      "name": "static_key_disable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:195",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581012608,
      "name": "static_key_disable_cpuslocked",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void static_key_disable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_disable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581069104,
      "name": "static_key_disable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:195",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069104,
      "name": "static_key_disable_cpuslocked",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void static_key_disable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_disable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581248896,
      "name": "static_key_disable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:195",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248896,
      "name": "static_key_disable_cpuslocked",
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
void static_key_disable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_disable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581290864,
      "name": "static_key_disable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:195",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_disable",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581290864,
      "name": "static_key_disable_cpuslocked",
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
void static_key_disable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_disable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581308528,
      "name": "static_key_disable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:195",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_disable",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581308528,
      "name": "static_key_disable_cpuslocked",
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
void static_key_disable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_disable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_disable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:195",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_disable",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592188891,
      "name": "static_key_disable_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581553456,
      "name": "static_key_disable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void static_key_disable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_disable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_disable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:195",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/jump_label.c:static_key_disable",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593963989,
      "name": "static_key_disable_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581905136,
      "name": "static_key_disable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void static_key_disable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_disable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_disable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:223",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/jump_label.c:static_key_disable",
        "mm/vmscan.c:lru_gen_change_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596023635,
      "name": "static_key_disable_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582339408,
      "name": "static_key_disable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void static_key_disable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_disable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_disable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:223",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/jump_label.c:static_key_disable",
        "mm/vmscan.c:lru_gen_change_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596545921,
      "name": "static_key_disable_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582541376,
      "name": "static_key_disable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void static_key_disable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_disable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_disable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:223",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_feat_write",
        "kernel/jump_label.c:static_key_disable",
        "mm/vmscan.c:lru_gen_change_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597449700,
      "name": "static_key_disable_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582710528,
      "name": "static_key_disable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void static_key_disable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_disable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492429880,
      "name": "static_key_disable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:195",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492429880,
      "name": "static_key_disable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void static_key_disable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_disable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285698064,
      "name": "static_key_disable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:195",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285698064,
      "name": "static_key_disable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void static_key_disable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_disable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581037952,
      "name": "static_key_disable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:195",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037952,
      "name": "static_key_disable_cpuslocked",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void static_key_disable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_disable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580984032,
      "name": "static_key_disable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:195",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984032,
      "name": "static_key_disable_cpuslocked",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void static_key_disable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_disable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581029152,
      "name": "static_key_disable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:195",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029152,
      "name": "static_key_disable_cpuslocked",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void static_key_disable_cpuslocked(struct static_key * key)
```

```json
{
  "name": "static_key_disable_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581090576,
      "name": "static_key_disable_cpuslocked",
      "external": true,
      "loc": "kernel/jump_label.c:195",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/jump_label.c:static_key_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090576,
      "name": "static_key_disable_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void static_key_disable_cpuslocked(struct static_key * key)
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
void static_key_disable_cpuslocked(struct static_key * key)
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
void static_key_disable_cpuslocked(struct static_key * key)
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
