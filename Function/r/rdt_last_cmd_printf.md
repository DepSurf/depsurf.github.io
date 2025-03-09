# Function: <code>rdt_last_cmd_printf</code>

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
void rdt_last_cmd_printf(const char * fmt, void (anon))
```

```json
{
  "name": "rdt_last_cmd_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579132944,
      "name": "rdt_last_cmd_printf",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:70",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132944,
      "name": "rdt_last_cmd_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void rdt_last_cmd_printf(const char * fmt, void (anon))
```

```json
{
  "name": "rdt_last_cmd_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579142592,
      "name": "rdt_last_cmd_printf",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:70",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:parse_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142592,
      "name": "rdt_last_cmd_printf",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char * fmt, void (anon))
```

```json
{
  "name": "rdt_last_cmd_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579205408,
      "name": "rdt_last_cmd_printf",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:74",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579205408,
      "name": "rdt_last_cmd_printf",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char * fmt, void (anon))
```

```json
{
  "name": "rdt_last_cmd_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579218336,
      "name": "rdt_last_cmd_printf",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:68",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579218336,
      "name": "rdt_last_cmd_printf",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char * fmt, void (anon))
```

```json
{
  "name": "rdt_last_cmd_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579220656,
      "name": "rdt_last_cmd_printf",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:68",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579220656,
      "name": "rdt_last_cmd_printf",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char * fmt, void (anon))
```

```json
{
  "name": "rdt_last_cmd_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579244400,
      "name": "rdt_last_cmd_printf",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:68",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_cstates_constrain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579244400,
      "name": "rdt_last_cmd_printf",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char * fmt, void (anon))
```

```json
{
  "name": "rdt_last_cmd_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579237248,
      "name": "rdt_last_cmd_printf",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:68",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_cstates_constrain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579237248,
      "name": "rdt_last_cmd_printf",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char * fmt, void (anon))
```

```json
{
  "name": "rdt_last_cmd_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579238672,
      "name": "rdt_last_cmd_printf",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:68",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579238672,
      "name": "rdt_last_cmd_printf",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char * fmt, void (anon))
```

```json
{
  "name": "rdt_last_cmd_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579275856,
      "name": "rdt_last_cmd_printf",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:71",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275856,
      "name": "rdt_last_cmd_printf",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char * fmt, void (anon))
```

```json
{
  "name": "rdt_last_cmd_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579329680,
      "name": "rdt_last_cmd_printf",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:71",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329680,
      "name": "rdt_last_cmd_printf",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char * fmt, void (anon))
```

```json
{
  "name": "rdt_last_cmd_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579397952,
      "name": "rdt_last_cmd_printf",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:71",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579397952,
      "name": "rdt_last_cmd_printf",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char * fmt, void (anon))
```

```json
{
  "name": "rdt_last_cmd_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579409904,
      "name": "rdt_last_cmd_printf",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:71",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409904,
      "name": "rdt_last_cmd_printf",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char * fmt, void (anon))
```

```json
{
  "name": "rdt_last_cmd_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579438864,
      "name": "rdt_last_cmd_printf",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:76",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579438864,
      "name": "rdt_last_cmd_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void rdt_last_cmd_printf(const char * fmt, void (anon))
```

```json
{
  "name": "rdt_last_cmd_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579219504,
      "name": "rdt_last_cmd_printf",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:68",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219504,
      "name": "rdt_last_cmd_printf",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char * fmt, void (anon))
```

```json
{
  "name": "rdt_last_cmd_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579154432,
      "name": "rdt_last_cmd_printf",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:68",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579154432,
      "name": "rdt_last_cmd_printf",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char * fmt, void (anon))
```

```json
{
  "name": "rdt_last_cmd_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579220576,
      "name": "rdt_last_cmd_printf",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:68",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579220576,
      "name": "rdt_last_cmd_printf",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void rdt_last_cmd_printf(const char * fmt, void (anon))
```

```json
{
  "name": "rdt_last_cmd_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579225936,
      "name": "rdt_last_cmd_printf",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:68",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_intel",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_bw_amd",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579225936,
      "name": "rdt_last_cmd_printf",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void rdt_last_cmd_printf(const char * fmt, void (anon))
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
void rdt_last_cmd_printf(const char * fmt, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void rdt_last_cmd_printf(const char * fmt, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void rdt_last_cmd_printf(const char * fmt, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void rdt_last_cmd_printf(const char * fmt, void (anon))
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
