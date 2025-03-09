# Function: <code>rdtgroup_kn_lock_live</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579123664,
      "name": "rdtgroup_kn_lock_live",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:699",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579123664,
      "name": "rdtgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579119296,
      "name": "rdtgroup_kn_lock_live",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1033",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579119296,
      "name": "rdtgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579133072,
      "name": "rdtgroup_kn_lock_live",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1101",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579133072,
      "name": "rdtgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579142720,
      "name": "rdtgroup_kn_lock_live",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1198",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142720,
      "name": "rdtgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579206688,
      "name": "rdtgroup_kn_lock_live",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1927",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206688,
      "name": "rdtgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579220384,
      "name": "rdtgroup_kn_lock_live",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1885",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579220384,
      "name": "rdtgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579222704,
      "name": "rdtgroup_kn_lock_live",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1883",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579222704,
      "name": "rdtgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579247488,
      "name": "rdtgroup_kn_lock_live",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1987",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579247488,
      "name": "rdtgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579240656,
      "name": "rdtgroup_kn_lock_live",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2038",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579240656,
      "name": "rdtgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579240928,
      "name": "rdtgroup_kn_lock_live",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2038",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579240928,
      "name": "rdtgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579281056,
      "name": "rdtgroup_kn_lock_live",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1991",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579281056,
      "name": "rdtgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579334960,
      "name": "rdtgroup_kn_lock_live",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1991",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334960,
      "name": "rdtgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579403456,
      "name": "rdtgroup_kn_lock_live",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2031",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403456,
      "name": "rdtgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579415536,
      "name": "rdtgroup_kn_lock_live",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2328",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579415536,
      "name": "rdtgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579444704,
      "name": "rdtgroup_kn_lock_live",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2411",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmid_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_closid_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444704,
      "name": "rdtgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579221552,
      "name": "rdtgroup_kn_lock_live",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1883",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221552,
      "name": "rdtgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579156480,
      "name": "rdtgroup_kn_lock_live",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1883",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579156480,
      "name": "rdtgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579222624,
      "name": "rdtgroup_kn_lock_live",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1883",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579222624,
      "name": "rdtgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579228016,
      "name": "rdtgroup_kn_lock_live",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1883",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579228016,
      "name": "rdtgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
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
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct rdtgroup * rdtgroup_kn_lock_live(struct kernfs_node * kn)
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
