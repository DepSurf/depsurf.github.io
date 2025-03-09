# Function: <code>free_rmid</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void free_rmid(u32 rmid)
```

```json
{
  "name": "free_rmid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579125056,
      "name": "free_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:211",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:free_all_child_rdtgrp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579125056,
      "name": "free_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
void free_rmid(u32 rmid)
```

```json
{
  "name": "free_rmid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579139344,
      "name": "free_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:211",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:free_all_child_rdtgrp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579139344,
      "name": "free_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
void free_rmid(u32 rmid)
```

```json
{
  "name": "free_rmid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579149296,
      "name": "free_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:211",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:free_all_child_rdtgrp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579149296,
      "name": "free_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void free_rmid(u32 rmid)
```

```json
{
  "name": "free_rmid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579215728,
      "name": "free_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:208",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579215728,
      "name": "free_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void free_rmid(u32 rmid)
```

```json
{
  "name": "free_rmid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:200",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230297,
      "name": "free_rmid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071579228768,
      "name": "free_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void free_rmid(u32 rmid)
```

```json
{
  "name": "free_rmid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579230992,
      "name": "free_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:200",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230992,
      "name": "free_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
void free_rmid(u32 rmid)
```

```json
{
  "name": "free_rmid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579254528,
      "name": "free_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:200",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579254528,
      "name": "free_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void free_rmid(u32 rmid)
```

```json
{
  "name": "free_rmid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579247408,
      "name": "free_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:263",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579247408,
      "name": "free_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void free_rmid(u32 rmid)
```

```json
{
  "name": "free_rmid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579249648,
      "name": "free_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:263",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579249648,
      "name": "free_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void free_rmid(u32 rmid)
```

```json
{
  "name": "free_rmid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579290240,
      "name": "free_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:263",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579290240,
      "name": "free_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void free_rmid(u32 rmid)
```

```json
{
  "name": "free_rmid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579344656,
      "name": "free_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:263",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344656,
      "name": "free_rmid",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void free_rmid(u32 rmid)
```

```json
{
  "name": "free_rmid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414512,
      "name": "free_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:352",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414512,
      "name": "free_rmid",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void free_rmid(u32 rmid)
```

```json
{
  "name": "free_rmid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579426960,
      "name": "free_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:369",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426960,
      "name": "free_rmid",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void free_rmid(u32 rmid)
```

```json
{
  "name": "free_rmid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579456544,
      "name": "free_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:369",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456544,
      "name": "free_rmid",
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
void free_rmid(u32 rmid)
```

```json
{
  "name": "free_rmid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579229840,
      "name": "free_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:200",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229840,
      "name": "free_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
void free_rmid(u32 rmid)
```

```json
{
  "name": "free_rmid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579165008,
      "name": "free_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:200",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579165008,
      "name": "free_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void free_rmid(u32 rmid)
```

```json
{
  "name": "free_rmid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579230912,
      "name": "free_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:200",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230912,
      "name": "free_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
void free_rmid(u32 rmid)
```

```json
{
  "name": "free_rmid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579236320,
      "name": "free_rmid",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:200",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236320,
      "name": "free_rmid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
void free_rmid(u32 rmid)
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
void free_rmid(u32 rmid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void free_rmid(u32 rmid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void free_rmid(u32 rmid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void free_rmid(u32 rmid)
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
