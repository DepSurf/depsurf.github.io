# Function: <code>rdtgroup_kn_unlock</code>

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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579123776,
      "name": "rdtgroup_kn_unlock",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:718",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579123776,
      "name": "rdtgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579119408,
      "name": "rdtgroup_kn_unlock",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1052",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579119408,
      "name": "rdtgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579133184,
      "name": "rdtgroup_kn_unlock",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1120",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579133184,
      "name": "rdtgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579142832,
      "name": "rdtgroup_kn_unlock",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1217",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142832,
      "name": "rdtgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579206800,
      "name": "rdtgroup_kn_unlock",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1946",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206800,
      "name": "rdtgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579220512,
      "name": "rdtgroup_kn_unlock",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1904",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579220512,
      "name": "rdtgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579222832,
      "name": "rdtgroup_kn_unlock",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1902",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579222832,
      "name": "rdtgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579247616,
      "name": "rdtgroup_kn_unlock",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2006",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579247616,
      "name": "rdtgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579240784,
      "name": "rdtgroup_kn_unlock",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2057",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579240784,
      "name": "rdtgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579241056,
      "name": "rdtgroup_kn_unlock",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2057",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579241056,
      "name": "rdtgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579281184,
      "name": "rdtgroup_kn_unlock",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2010",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579281184,
      "name": "rdtgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579335088,
      "name": "rdtgroup_kn_unlock",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2010",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579335088,
      "name": "rdtgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579403600,
      "name": "rdtgroup_kn_unlock",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2050",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403600,
      "name": "rdtgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579415680,
      "name": "rdtgroup_kn_unlock",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2346",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579415680,
      "name": "rdtgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579444848,
      "name": "rdtgroup_kn_unlock",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2429",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmid_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_closid_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444848,
      "name": "rdtgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579221680,
      "name": "rdtgroup_kn_unlock",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1902",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221680,
      "name": "rdtgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579156608,
      "name": "rdtgroup_kn_unlock",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1902",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579156608,
      "name": "rdtgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579222752,
      "name": "rdtgroup_kn_unlock",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1902",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579222752,
      "name": "rdtgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579228144,
      "name": "rdtgroup_kn_unlock",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1902",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579228144,
      "name": "rdtgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
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
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node * kn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void rdtgroup_kn_unlock(struct kernfs_node * kn)
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
