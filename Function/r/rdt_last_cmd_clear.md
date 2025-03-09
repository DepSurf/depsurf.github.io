# Function: <code>rdt_last_cmd_clear</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rdt_last_cmd_clear()
```

```json
{
  "name": "rdt_last_cmd_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579136677,
      "name": "rdt_last_cmd_clear",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:58",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132864,
      "name": "rdt_last_cmd_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void rdt_last_cmd_clear()
```

```json
{
  "name": "rdt_last_cmd_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579146322,
      "name": "rdt_last_cmd_clear",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:58",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142512,
      "name": "rdt_last_cmd_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void rdt_last_cmd_clear()
```

```json
{
  "name": "rdt_last_cmd_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579211969,
      "name": "rdt_last_cmd_clear",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:62",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579205328,
      "name": "rdt_last_cmd_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void rdt_last_cmd_clear()
```

```json
{
  "name": "rdt_last_cmd_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579225665,
      "name": "rdt_last_cmd_clear",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:56",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579218256,
      "name": "rdt_last_cmd_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void rdt_last_cmd_clear()
```

```json
{
  "name": "rdt_last_cmd_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579217880,
      "name": "rdt_last_cmd_clear",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:56",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579220576,
      "name": "rdt_last_cmd_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void rdt_last_cmd_clear()
```

```json
{
  "name": "rdt_last_cmd_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579242781,
      "name": "rdt_last_cmd_clear",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:56",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579244320,
      "name": "rdt_last_cmd_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void rdt_last_cmd_clear()
```

```json
{
  "name": "rdt_last_cmd_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579235695,
      "name": "rdt_last_cmd_clear",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:56",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579237168,
      "name": "rdt_last_cmd_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void rdt_last_cmd_clear()
```

```json
{
  "name": "rdt_last_cmd_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579237451,
      "name": "rdt_last_cmd_clear",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:56",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579238592,
      "name": "rdt_last_cmd_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void rdt_last_cmd_clear()
```

```json
{
  "name": "rdt_last_cmd_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579279964,
      "name": "rdt_last_cmd_clear",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:59",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275776,
      "name": "rdt_last_cmd_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void rdt_last_cmd_clear()
```

```json
{
  "name": "rdt_last_cmd_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579333770,
      "name": "rdt_last_cmd_clear",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:59",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329584,
      "name": "rdt_last_cmd_clear",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rdt_last_cmd_clear()
```

```json
{
  "name": "rdt_last_cmd_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579402250,
      "name": "rdt_last_cmd_clear",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:59",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579397824,
      "name": "rdt_last_cmd_clear",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rdt_last_cmd_clear()
```

```json
{
  "name": "rdt_last_cmd_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579408964,
      "name": "rdt_last_cmd_clear",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:59",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mbm_local_bytes_config_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mbm_total_bytes_config_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409776,
      "name": "rdt_last_cmd_clear",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rdt_last_cmd_clear()
```

```json
{
  "name": "rdt_last_cmd_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579437908,
      "name": "rdt_last_cmd_clear",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:64",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mbm_local_bytes_config_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mbm_local_bytes_config_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mbm_total_bytes_config_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mbm_total_bytes_config_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579438736,
      "name": "rdt_last_cmd_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void rdt_last_cmd_clear()
```

```json
{
  "name": "rdt_last_cmd_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579216728,
      "name": "rdt_last_cmd_clear",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:56",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219424,
      "name": "rdt_last_cmd_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void rdt_last_cmd_clear()
```

```json
{
  "name": "rdt_last_cmd_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579151320,
      "name": "rdt_last_cmd_clear",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:56",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579154352,
      "name": "rdt_last_cmd_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void rdt_last_cmd_clear()
```

```json
{
  "name": "rdt_last_cmd_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579217800,
      "name": "rdt_last_cmd_clear",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:56",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579220496,
      "name": "rdt_last_cmd_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void rdt_last_cmd_clear()
```

```json
{
  "name": "rdt_last_cmd_clear",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579223112,
      "name": "rdt_last_cmd_clear",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:56",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_show"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579225856,
      "name": "rdt_last_cmd_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void rdt_last_cmd_clear()
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void rdt_last_cmd_clear()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void rdt_last_cmd_clear()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void rdt_last_cmd_clear()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void rdt_last_cmd_clear()
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
