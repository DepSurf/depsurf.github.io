# Function: <code>kernfs_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581504112,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:531",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_iop_lookup",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/dir.c:kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:sysfs_remove_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581504112,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581689664,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:530",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_remove",
        "fs/kernfs/dir.c:kernfs_iop_lookup",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581689664,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581778592,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:480",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_remove",
        "fs/kernfs/dir.c:kernfs_iop_lookup",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581778592,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581833664,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:490",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_iop_lookup",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581833664,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581983120,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:491",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581983120,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582170864,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:491",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582170864,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582265936,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:491",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582265936,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:490",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582437110,
      "name": "kernfs_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071582430080,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582528864,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:491",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528864,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582834336,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:491",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/kernfs/inode.c:kernfs_init_inode",
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_do_create_link_sd",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582834336,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582907088,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:491",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/kernfs/inode.c:kernfs_init_inode",
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_do_create_link_sd",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582907088,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582934880,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:491",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_do_create_link_sd",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582934880,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583272618,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:493",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_get_parent"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_do_create_link_sd",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583269728,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583776705,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:501",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_get_parent"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_do_create_link_sd",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583773056,
      "name": "kernfs_get",
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584394672,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:522",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_get_parent"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_do_create_link_sd",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584390624,
      "name": "kernfs_get",
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584623108,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:519",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_get_parent"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_do_create_link_sd",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584619008,
      "name": "kernfs_get",
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584855604,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:523",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_get_parent"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_do_create_link_sd",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584849776,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494162792,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:491",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494162792,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227601528,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:491",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_do_create_link_sd",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227601528,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287839888,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:491",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287839888,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273634410,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:491",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_get_parent"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273630804,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582497600,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:491",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582497600,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582434832,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:491",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582434832,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582488080,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:491",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582488080,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void kernfs_get(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582568640,
      "name": "kernfs_get",
      "external": true,
      "loc": "fs/kernfs/dir.c:491",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/kernfs/inode.c:kernfs_get_inode",
        "fs/kernfs/dir.c:kernfs_fop_readdir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_walk_and_get_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_ns",
        "fs/kernfs/dir.c:kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_get_parent",
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_add_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582568640,
      "name": "kernfs_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
