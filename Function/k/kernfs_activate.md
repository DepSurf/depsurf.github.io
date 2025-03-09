# Function: <code>kernfs_activate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581509728,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1159",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:rebind_subsystems",
        "kernel/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_setup_root",
        "fs/kernfs/dir.c:kernfs_add_one",
        "fs/kernfs/dir.c:kernfs_create_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581509728,
      "name": "kernfs_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581695408,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1207",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_setup_root",
        "kernel/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581695408,
      "name": "kernfs_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581783376,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1158",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init",
        "kernel/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_setup_root",
        "kernel/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581783376,
      "name": "kernfs_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581838176,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1168",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581838176,
      "name": "kernfs_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581987904,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1233",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581987904,
      "name": "kernfs_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582175488,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1256",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582175488,
      "name": "kernfs_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582270624,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1256",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270624,
      "name": "kernfs_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582435008,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1257",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582435008,
      "name": "kernfs_activate",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582533744,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1257",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582533744,
      "name": "kernfs_activate",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582839456,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1261",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_setup_root",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582839456,
      "name": "kernfs_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582912208,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1260",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_setup_root",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582912208,
      "name": "kernfs_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582939904,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1262",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582939904,
      "name": "kernfs_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583275040,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1289",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583275040,
      "name": "kernfs_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583778944,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1320",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583778944,
      "name": "kernfs_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584397232,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1369",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584397232,
      "name": "kernfs_activate",
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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584625696,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1373",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584625696,
      "name": "kernfs_activate",
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584857952,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1389",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584857952,
      "name": "kernfs_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494167768,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1257",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494167768,
      "name": "kernfs_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227607564,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1257",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227607564,
      "name": "kernfs_activate",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287851696,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1257",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287851696,
      "name": "kernfs_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273636568,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1257",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273636568,
      "name": "kernfs_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582502480,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1257",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582502480,
      "name": "kernfs_activate",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582439696,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1257",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582439696,
      "name": "kernfs_activate",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582492960,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1257",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582492960,
      "name": "kernfs_activate",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void kernfs_activate(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582573600,
      "name": "kernfs_activate",
      "external": true,
      "loc": "fs/kernfs/dir.c:1257",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_add_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582573600,
      "name": "kernfs_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
