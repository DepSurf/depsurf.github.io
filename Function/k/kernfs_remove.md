# Function: <code>kernfs_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581510800,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1252",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:sysfs_remove_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510800,
      "name": "kernfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581696432,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1301",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581696432,
      "name": "kernfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581784400,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1252",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "kernel/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784400,
      "name": "kernfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581839152,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1262",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_all",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839152,
      "name": "kernfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581988896,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1327",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_all",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581988896,
      "name": "kernfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582176464,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1350",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_all",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582176464,
      "name": "kernfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582271600,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1350",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271600,
      "name": "kernfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582435984,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1350",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582435984,
      "name": "kernfs_remove",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582534720,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1350",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582534720,
      "name": "kernfs_remove",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582839390,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1354",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_destroy_root"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_add_file",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582840656,
      "name": "kernfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582912142,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1353",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_destroy_root"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_add_file",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582913408,
      "name": "kernfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582939838,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1355",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_destroy_root"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582941104,
      "name": "kernfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583274974,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1382",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_destroy_root"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583276272,
      "name": "kernfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583780288,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1417",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583780288,
      "name": "kernfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584398784,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1486",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584398784,
      "name": "kernfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584627328,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1493",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584627328,
      "name": "kernfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584859488,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1509",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584859488,
      "name": "kernfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494168968,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1350",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494168968,
      "name": "kernfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227608744,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1350",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227608744,
      "name": "kernfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287853312,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1350",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287853312,
      "name": "kernfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273637576,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1350",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273637576,
      "name": "kernfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582503456,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1350",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582503456,
      "name": "kernfs_remove",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582440672,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1350",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440672,
      "name": "kernfs_remove",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582493936,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1350",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582493936,
      "name": "kernfs_remove",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582574576,
      "name": "kernfs_remove",
      "external": true,
      "loc": "fs/kernfs/dir.c:1350",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/sysfs/dir.c:sysfs_remove_dir",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582574576,
      "name": "kernfs_remove",
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
